# AGENTS.md

## Site Overview

Hugo static site using the [Ananke](themes/ananke) theme (git submodule). Portuguese-language personal blog deployed to GitHub Pages at `danilomarroco.github.io/meu-blog/`.

## Key Commands

```bash
# Build site (outputs to public/)
hugo

# Development server with live reload
hugo server

# Create new post using archetype
hugo new posts/my-post-name.md
```

Requires **Hugo Extended** version (v0.146.0+).

## Theme Setup

Theme is installed as a **git submodule** in `themes/ananke`.

```bash
# After cloning, download submodules
git submodule update --init --recursive

# Update theme
cd themes/ananke && git pull origin main
```

## Content Structure

- `content/posts/` - Blog posts (Markdown)
- `content/about.md` - About page
- `hugo.toml` - Main configuration
- `config/_default/params.toml` - Theme parameters
- `archetypes/posts.md` - Post template

## Configuration

- Main config: `hugo.toml` - site title, URLs, markup settings
- Theme params: `config/_default/params.toml` - social links, menus, date format
- Brazilian date format: `"02 de Janeiro de 2006"`

## CI/CD

GitHub Actions (`.github/workflows/deploy.yml`) deploys on push to `main`:
1. Installs Hugo Extended v0.157.0
2. Checks out with submodules (`--recursive`)
3. Runs `hugo --gc --minify`
4. Uploads `public/` to GitHub Pages

## What This Theme Does NOT Have

Unlike FixIt, Ananke does **not** include:
- Built-in search (Lunr)
- Comments system
- Image lightbox/gallery
- Dark/light mode toggle
- Table of contents per post
- Admonition shortcodes
