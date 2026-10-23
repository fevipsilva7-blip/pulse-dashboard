#  Pulse — Dashboard em React

> Painel administrativo responsivo com KPIs, gráficos de linha, barra e pizza, tabela de pedidos e tema claro/escuro.

[![Demo](https://img.shields.io/badge/Demo-ao%20vivo-00C2B8?style=for-the-badge&logo=vercel&logoColor=white)](https://react-dashboard2-tau.vercel.app/)
![Status](https://img.shields.io/badge/status-em%20evolu%C3%A7%C3%A3o-007BFF?style=for-the-badge)

<!-- Quando tiver um print ou GIF, salve em docs/preview.png e descomente a linha abaixo:
![Preview do Pulse Dashboard](docs/preview.png)
-->

> Os dados exibidos são fictícios e ficam em `src/data/mockData.js`.

---

##  Sobre o projeto

Projeto criado para praticar a construção de interfaces de dados com React: componentização, visualização com gráficos, temas claro/escuro e layout responsivo, simulando um painel de vendas de e-commerce.

###  Funcionalidades

- Cards de KPI (receita, pedidos, visitantes e conversão)
- Gráfico de receita mensal (linha)
- Gráfico de vendas por categoria (barra)
- Gráfico de origem de tráfego (pizza)
- Tabela de pedidos recentes com status
- Alternância entre tema claro e escuro
- Layout responsivo: a sidebar recolhe em telas pequenas

---

##  Tecnologias

![React](https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=flat-square)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Vercel](https://img.shields.io/badge/Deploy-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

- **React 18** para a interface e componentes reutilizáveis
- **Vite** como bundler e servidor de desenvolvimento
- **Recharts** para os gráficos

---

##  Como rodar localmente

### Pré-requisitos

- [Node.js](https://nodejs.org/) (versão LTS recomendada)
- [Git](https://git-scm.com/)

### Passo a passo

```bash
# 1. Clone o repositório
git clone https://github.com/fevipsilva7-blip/react-dashboard-.git

# 2. Entre na pasta
cd react-dashboard-

# 3. Instale as dependências
npm install

# 4. Inicie em modo desenvolvimento
npm run dev
```

Acesse o endereço que o Vite mostrar no terminal (normalmente **http://localhost:5173**).

Não é preciso configurar variáveis de ambiente nem chaves de API: os dados são locais.

### Scripts disponíveis

| Comando | O que faz |
|---|---|
| `npm run dev` | Inicia o servidor de desenvolvimento |
| `npm run build` | Gera a versão de produção na pasta `dist` |
| `npm run preview` | Visualiza localmente o build de produção |

---

##  Estrutura de pastas

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

---

##  Próximos passos

- [ ] Trocar `mockData.js` por chamadas a uma API real (por exemplo, um back-end em Node/Express)
- [ ] Adicionar filtro de período (últimos 7/30/90 dias)
- [ ] Adicionar autenticação
- [ ] Migrar para TypeScript

---

##  Autor

**Felipe Rodrigues**
[LinkedIn](https://www.linkedin.com/in/felipe-rodrigues-da-silvaa) · [Portfólio](https://portfolio-site-five-jet-79.vercel.app/) · [GitHub](https://github.com/fevipsilva7-blip)
