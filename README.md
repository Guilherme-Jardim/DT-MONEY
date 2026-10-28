# DT Money

Aplicação para controlar entradas e saídas financeiras. Dá para cadastrar transações, buscar por descrição e ver o resumo de entradas, saídas e total.

## Tecnologias

- React 18 e TypeScript
- Vite
- styled-components
- React Hook Form e Zod
- Radix UI (modal)
- Axios e json-server (API local fake)
- use-context-selector

## Como instalar e rodar

```bash
npm install
npm run dev:server   # API fake em http://localhost:3333
npm run dev          # aplicação em outro terminal
```

A aplicação depende da API local do json-server (arquivo `server.json`), então os dois comandos precisam estar rodando.

Outros comandos: `npm run build` gera a versão de produção e `npm run lint` roda o ESLint.
