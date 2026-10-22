# Pulse — Dashboard em React

[![Demo](https://img.shields.io/badge/DEMO-ff00c8?style=for-the-badge&logo=vercel&logoColor=white)](https://react-dashboard2-tau.vercel.app/)

Painel administrativo responsivo construído com **React + Vite + Recharts**, com KPIs, gráficos (linha, barra e pizza), tabela de pedidos e alternância de tema claro/escuro.

> Os dados exibidos são fictícios (`src/data/mockData.js`).

## Funcionalidades

- Cards de KPI (receita, pedidos, visitantes, conversão)
- Gráfico de receita mensal (linha)
- Gráfico de vendas por categoria (barra)
- Gráfico de origem de tráfego (pizza)
- Tabela de pedidos recentes com status
- Tema claro/escuro
- Layout responsivo (sidebar recolhe em telas pequenas)

## Como rodar

```bash
npm install
npm run dev
```

## Tecnologias

- React 18
- Vite
- Recharts

## Estrutura

```
.
├── src/
│   ├── components/
│   │   ├── Sidebar.jsx
│   │   ├── KpiCard.jsx
│   │   ├── RevenueChart.jsx
│   │   ├── CategoryChart.jsx
│   │   ├── TrafficChart.jsx
│   │   └── OrdersTable.jsx
│   ├── data/
│   │   └── mockData.js
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── package.json
└── vite.config.js
```

## Próximos passos

- Trocar `mockData.js` por chamadas a uma API real (por exemplo, um back-end em Node/Express)
- Adicionar filtro de período (últimos 7/30/90 dias)
- Adicionar autenticação
