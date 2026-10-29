# CODIFY — site estático

Site estático (HTML, CSS e JavaScript). Não precisa de build nem de dependências.

## Estrutura

```
codify/
├── index.html
├── 404.html
├── favicon.svg
├── robots.txt
├── vercel.json
├── css/style.css
└── js/script.js
```

## Publicar no Vercel

**Opção 1 — Arrastar e largar**
1. Vai a vercel.com e entra na tua conta.
2. Clica em *Add New → Project* e escolhe fazer upload da pasta `codify`.
3. Framework Preset: **Other**. Deixa Build Command e Output Directory vazios.
4. Clica em *Deploy*.

**Opção 2 — GitHub**
1. Cria um repositório e envia o conteúdo desta pasta.
2. No Vercel, *Add New → Project*, importa o repositório.
3. Framework Preset: **Other** → *Deploy*.

**Opção 3 — Terminal**
```
npm i -g vercel
cd codify
vercel --prod
```

## Funcionalidades

- Pedido de orçamento: o formulário abre o WhatsApp +244 958 835 941 com os dados preenchidos.
- Botão flutuante de WhatsApp, botão de voltar ao topo e barra de progresso.
- Menu que destaca a secção atual e menu mobile.
- Animações ao rolar (respeitam "reduzir movimento").
- Perguntas frequentes, página 404, favicon, meta tags para partilha e cabeçalhos de segurança.

## Para editar depois

- Número do WhatsApp: `WA_NUMBER` em `js/script.js`.
- Textos e secções: `index.html`.
- Cores e estilos: `css/style.css` (variáveis no topo).
