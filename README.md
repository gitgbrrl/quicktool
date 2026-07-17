# Toolbox Hub

Coleção de ferramentas online gratuitas — matemática, texto, conversores, datas, desenvolvimento e cores. Tudo roda no navegador, sem login e sem instalação.

## Estrutura

```
toolhub/
├── index.html   → Hub principal (Toolbox Hub) — ferramentas rápidas em modais
├── math.html    → MathTools — 100+ calculadoras e ferramentas matemáticas
└── text.html    → TextTools — 100+ ferramentas de texto e utilitários
```

### Como funciona

| Arquivo | Papel | Navegação |
|---------|-------|-----------|
| **index.html** | Portal central com busca, categorias, favoritos (localStorage) e ferramentas leves abertas em modal | Single-page, JavaScript vanilla |
| **math.html** | Suite matemática completa com sidebar, KaTeX, Chart.js, Math.js | `go('home' \| 'category' \| 'tool' \| ...)` |
| **text.html** | Suite de texto com hash routing | `#/`, `#/ferramenta/:id`, `#/favoritos` |

Os três sites compartilham o mesmo repositório e se linkam entre si pelo header.

## Uso local

Abra `index.html` no navegador ou sirva com qualquer servidor estático:

```bash
npx serve .
```

## GitHub Pages

1. Vá em **Settings → Pages**
2. Source: branch `main`, pasta `/ (root)`
3. Acesse `https://<usuario>.github.io/toolhub/`

## Tecnologias

- HTML, CSS, JavaScript (sem build)
- [Tailwind CSS](https://tailwindcss.com) (CDN)
- [Lucide Icons](https://lucide.dev)
- MathTools: KaTeX, Math.js, Chart.js, Plotly
- Dados salvos apenas no `localStorage` do navegador

## Licença

MIT
