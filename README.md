# Portfólio · Matheus Mangili

Landing page estática (sem build, sem dependências), publicada em
**https://matheushmangili-ux.github.io** via GitHub Pages.

- **`index.html`**: versão publicada (estilo agência): tipografia gigante, hero manifesto animado,
  marquee, grade estática de cards com ícones de monograma, tema escuro com verde-lima e grão de filme
- **`v1.html`**: versão alternativa minimalista (editorial, tema claro/escuro com toggle)

Ambas compartilham:

- Tipografia Geist auto-hospedada em `fonts/` (nada é carregado de CDN)
- Responsividade e acessibilidade (contraste AA, `prefers-reduced-motion` respeitado)

## Como atualizar o site

Edite os arquivos nesta pasta e rode:

```
git add .
git commit -m "Descreva a mudança"
git push
```

O GitHub Pages republica sozinho em 1 a 2 minutos.

## Como editar os projetos

Tudo está em `index.html`. Cada projeto é um bloco `<article class="card">`:

- Para adicionar: duplique um bloco e troque título, descrição, monograma (`.app-icon`) e tags.
- Para destacar: use `class="card lime"` (ocupa a largura toda, com fundo verde-lima).
- Os cards são estáticos por decisão de design; os links ficam na seção "Repos públicos".
