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

| Arquivo | Papel |
|---------|-------|
| **index.html** | Portal — escolha entre MathTools ou TextTools |
| **math.html** | Suite matemática completa (sidebar, KaTeX, Chart.js, Math.js) |
| **text.html** | Suite de texto (hash routing, favoritos, histórico) |

## Uso local

Abra `index.html` no navegador ou sirva com qualquer servidor estático:

```bash
npx serve .
```

## Tecnologias

- HTML, CSS, JavaScript (sem build)
- [Tailwind CSS](https://tailwindcss.com) (CDN)
- [Lucide Icons](https://lucide.dev)
- MathTools: KaTeX, Math.js, Chart.js, Plotly
- Dados salvos apenas no `localStorage` do navegador

## Licença

MIT
