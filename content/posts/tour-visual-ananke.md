---
title: "Tour Visual pelo Tema Ananke"
featured_image: "/images/posts/2026/02/hello.jpg"
date: 2026-04-11
draft: false
author: "Danilo Marroco"
description: "Um post completo para testar os recursos visuais do tema Ananke"
tags: ["Teste", "Visual", "Hugo", "Ananke"]
categories: ["Tecnologia"]
images: ["/images/posts/2026/02/hello.jpg"]
---

Este post demonstra os diferentes recursos visuais disponíveis no tema Ananke. Vamos explorar imagens, tabelas, código, citações e muito mais!

<!--more-->

## Imagens Inline

As imagens podem ser adicionadas diretamente no conteúdo usando a sintaxe padrão Markdown:

![Paisagem de exemplo](https://images.unsplash.com/photo-1506905925346-21bda4d32df4?w=800&q=80)

### Imagens com Link

[![Paisagem clicável](https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?w=600&q=80)](https://unsplash.com)

---

## Citações e Blockquotes

> "A simplicidade é a sofisticação máxima."
> — Leonardo da Vinci

> **Nota importante:** Este é um exemplo de citação destacada com conteúdo adicional que pode ocupar múltiplas linhas para demonstrar como o tema formata textos de citação longos.

---

## Tabelas

| Recurso | Status | Observações |
|---------|--------|------------|
| Imagens | ✅ Funcional | Suporta inline e featured |
| Tabelas | ✅ Funcional | Estilo nativo |
| Código | ✅ Funcional | Syntax highlighting |
| Blockquotes | ✅ Funcional | Estilizado |
| Tarefas | ✅ Funcional | Checklists Markdown |

---

## Blocos de Código

### Python
```python
def calcular_fibonacci(n):
    """Calcula o n-ésimo número de Fibonacci."""
    if n <= 1:
        return n
    return calcular_fibonacci(n-1) + calcular_fibonacci(n-2)

# Exemplo de uso
for i in range(10):
    print(f"F({i}) = {calcular_fibonacci(i)}")
```

### JavaScript
```javascript
const saudacao = (nome) => {
    return `Olá, ${nome}! Bem-vindo ao blog.`;
};

console.log(saudacao('Visitante'));
```

### Bash
```bash
#!/bin/bash
echo "Build do site Hugo"
hugo --gc --minify
```

---

## Listas de Tarefas

- [x] Criar post de teste visual
- [x] Incluir imagens
- [x] Adicionar tabela de recursos
- [x] Demonstrar código com highlighting
- [ ] Testar modo escuro (não disponível neste tema)
- [ ] Explorar mais personalizações

---

## Texto Formatado

O tema suporta **negrito**, *itálico*, ~~riscado~~ e `código inline`.

Você também pode usar _underscore_ para ênfase e combinações como **_negrito e itálico_** para destaques importantes.

---

## Links e Referências

Visite o [site do Hugo](https://gohugo.io) para mais informações.

Emails funcionam assim: [meu-email@exemplo.com](mailto:meu-email@exemplo.com)

---

## Conclusão

O tema Ananke oferece uma experiência visual limpa e minimalista. Embora não tenha todos os recursos avançados do FixIt (como galeria de imagens ou busca integrada), sua simplicidade o torna rápido e fácil de manter.

**Próximos passos:**
1. Personalizar cores no CSS
2. Adicionar mais posts
3. Configurar comentários (Disqus ou Giscus)
