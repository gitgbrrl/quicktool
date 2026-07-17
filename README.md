# QuickTool

Ferramentas online gratuitas de matemática e texto. Tudo roda no navegador, sem login e sem instalação.

## Estrutura

```
quicktool/
├── index.html           → Portal (QuickTool)
├── matematica/index.html → Ferramentas de matemática
└── texto/index.html      → Ferramentas de texto
```

### URLs

| Caminho | Conteúdo |
|---------|----------|
| `/` | Portal QuickTool |
| `/matematica/` | Ferramentas de matemática |
| `/texto/` | Ferramentas de texto |

## Uso local

Sirva com um servidor estático (necessário para URLs limpas):

```bash
npx serve .
```

Depois acesse `http://localhost:3000/`, `/matematica/` e `/texto/`.

## Tecnologias

- HTML, CSS, JavaScript (sem build)
- Matemática: KaTeX, Math.js, Chart.js, Plotly
- Dados salvos apenas no `localStorage` do navegador

## Licença

MIT
