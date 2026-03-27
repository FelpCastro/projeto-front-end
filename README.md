# 👟 Digital Store - E-Commerce
<p align="center"> <img src="https://img.shields.io/badge/React-19.2.0-blue" alt="React Version" /> <img src="https://img.shields.io/badge/Vite-7.3.1-yellow" alt="Vite Version" /> <img src="https://img.shields.io/badge/TailwindCSS-4.2.1-cyan" alt="TailwindCSS Version" /> <img src="https://img.shields.io/badge/Node.js-18+-green" alt="Node.js Version" /> <img src="https://img.shields.io/badge/License-MIT-lightgrey" alt="License" /> </p> <p align="center"> <strong>Plataforma completa de e-commerce para tênis e lifestyle, com foco em UX intuitiva, filtros avançados e navegação rápida.</strong> </p>

# 📋 Sobre o Projeto
<p>A Digital Store é um projeto de e-commerce moderno desenvolvido em React, simulando uma loja online de tênis e acessórios. O foco está em uma experiência de usuário fluida, com sistema de busca, filtros dinâmicos, carrinho de compras persistente e design responsivo. Atualmente, utiliza dados mockados localmente, mas está preparado para integração com um backend (como Supabase) para autenticação e gerenciamento de produtos.</p>

### 🚀 Link do Deploy: 
https://projeto-front-end-rouge.vercel.app/

# ✨ Funcionalidades em Destaque
<p>🔍 Sistema de Busca e Filtros Avançados: Busque produtos por nome, categoria, marca (Nike, Adidas, etc.) e faixa de preço.</p>

<p>🛒 Carrinho de Compras Interativo: Adicione/remova produtos, ajuste quantidades e veja o total em tempo real. Estado persistido no navegador.</p>

<p>📱 Design Fully Responsive: Otimizado para desktop, tablets e mobile, com navegação intuitiva.</p>

<p>⚡ Performance Otimizada: Carregamento rápido usando Vite e React Router para roteamento SPA.</p>

<p>🔒 Autenticação e Cadastro: Páginas para login, cadastro e completar perfil (preparado para integração com backend).</p>

<p>🖼️ Galeria de Imagens: Visualização detalhada de produtos com múltiplas fotos.</p>

<p>📊 Listagem de Produtos: Páginas dedicadas para categorias, produtos relacionados e visualização individual.</p>

<p>🎨 Estilização Moderna: Utiliza Tailwind CSS para um design limpo e customizável.</p>

# 🛠️ Tecnologias Utilizadas
## Frontend:

º React (v19.2.0) - Biblioteca para construção de interfaces.
º Vite (v7.3.1) - Ferramenta de build e desenvolvimento rápido.
º React Router DOM (v7.13.1) - Roteamento para navegação SPA.
º Tailwind CSS (v4.2.1) - Framework CSS para estilização utilitária.
º Axios (v1.13.6) - Cliente HTTP para requisições (configurado para backend local).
º React Icons (v5.6.0) - Ícones para UI.

## Ferramentas de Desenvolvimento:
º ESLint - Linting para qualidade de código.
º PostCSS - Processamento de CSS.
º Autoprefixer - Adição automática de prefixos CSS.

## Futuro/Backend Planejado:
º Supabase - Para banco de dados, autenticação e API (não implementado ainda).

# 📂 Estrutura do Projeto (Arquitetura Atômica
```
├── src/
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
│   ├── assets/
│   │   └── (recursos como imagens ou fontes)
│   ├── components/
│   │   ├── authLinks.jsx
│   │   ├── buyBox.jsx
│   │   ├── cartDropDown.jsx
│   │   ├── cartIcon.jsx
│   │   ├── filterGroup.jsx
│   │   ├── footer.jsx
│   │   ├── gallery.jsx
│   │   ├── header.jsx
│   │   ├── hero.jsx
│   │   ├── imageGallery.jsx
│   │   ├── logo.jsx
│   │   ├── mainNave.jsx
│   │   ├── productInfo.jsx
│   │   ├── productOptions.jsx
│   │   ├── relatedProducts.jsx
│   │   ├── searchBar.jsx
│   │   ├── section.jsx
│   │   ├── AbaProdutos/
│   │   │   ├── productCardList.jsx
│   │   │   └── productListingList.jsx
│   │   └── HomePage/
│   │       ├── productCard.jsx
│   │       └── productListing.jsx
│   ├── contexts/
│   │   └── cartContext.jsx
│   ├── data/
│   │   └── products.js
│   ├── pages/
│   │   ├── cadastro.jsx
│   │   ├── categoriasPage.jsx
│   │   ├── completarCadastro.jsx
│   │   ├── homePage.jsx
│   │   ├── layout.jsx
│   │   ├── login.jsx
│   │   ├── meusPedidosPage.jsx
│   │   ├── productListingPage.jsx
│   │   ├── productPage.jsx
│   │   ├── productViewPage.jsx
│   │   └── (outros arquivos de página)
│   └── services/
│       └── api.js
├── public/
│   └── (arquivos estáticos, ex.: imagens ou ícones)
├── eslint.config.js
├── index.html
├── package.json
├── postcss.config.js
├── react-router.config.js
├── README.md
├── tailwind.config.js
└── vite.config.js```  
