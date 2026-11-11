# Scoreboard semanal do NOC

Página estática (HTML/CSS/JS puro), sem dependências de build.

## Autoria
jorge.felix - [jorge.felix@byseven.com.br](mailto:jorge.felix@byseven.com.br)

## Estrutura
- `index.html`: entrada do site; o Scoreboard abre como padrão e a barra superior alterna entre as aplicações
- `tabs/it-assistente/index.html`: IT Assistente, com criação e conferência de documentos
- `assets/background/background_by7.png`: wallpaper transparente, exibido apenas no tema BySeven (escuro)
- `assets/icons/favicon.svg`: ícone da aba

## Temas
- **Escuro (padrão): BySeven**
- **Claro: Voke** (rosa e azul). Sem imagem de fundo: a marca "voke" é gerada em CSS, em azul
- A escolha fica salva no navegador e é sincronizada com o IT Assistente. Cores editáveis nas variáveis `:root` e `:root[data-theme="light"]` no topo do `index.html`.

## Publicar no GitHub Pages
1. Crie um repositório e envie o conteúdo desta pasta.
2. Settings > Pages > Source: branch `main`, pasta `/ (root)`.

## Observação
Os dados são salvos no `localStorage` do navegador de cada usuário (não são compartilhados entre máquinas). A chave foi mantida (`scoreboard-noc-v4`), então os dados já preenchidos continuam disponíveis.
