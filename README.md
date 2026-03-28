# 👟 Digital Store - E-Commerce
<p align="center"> <img src="https://img.shields.io/badge/React-19.2.0-blue" alt="React Version" /> <img src="https://img.shields.io/badge/Vite-7.3.1-yellow" alt="Vite Version" /> <img src="https://img.shields.io/badge/TailwindCSS-4.2.1-cyan" alt="TailwindCSS Version" /> <img src="https://img.shields.io/badge/Node.js-18+-green" alt="Node.js Version" /> <img src="https://img.shields.io/badge/License-MIT-lightgrey" alt="License" /> <img src="https://img.shields.io/github/stars/FelpCastro/projeto-front-end?style=social" alt="GitHub Stars" /> </p> <p align="center"> <strong>Plataforma completa de e-commerce para tênis e lifestyle, com foco em UX intuitiva, filtros avançados e navegação rápida.</strong> </p>

# 📋 Sobre o Projeto
A Digital Store é um projeto de e-commerce moderno desenvolvido em React, simulando uma loja online de tênis e acessórios. O foco está em uma experiência de usuário fluida, com sistema de busca, filtros dinâmicos, carrinho de compras persistente e design responsivo. Atualmente, utiliza dados mockados localmente, mas está preparado para integração com um backend (como Supabase) para autenticação e gerenciamento de produtos.

# 🚀 Link do Deploy
https://projeto-front-end-rouge.vercel.app/

#✨ Funcionalidades em Destaque
<p>🔍 Sistema de Busca e Filtros Avançados: Busque produtos por nome, categoria, marca (Nike, Adidas, etc.) e faixa de preço.</p>
<p>🛒 Carrinho de Compras Interativo: Adicione/remova produtos, ajuste quantidades e veja o total em tempo real. Estado persistido no navegador.</p>
<p>📱 Design Fully Responsive: Otimizado para desktop, tablets e mobile, com navegação intuitiva.</p>
<p>⚡ Performance Otimizada: Carregamento rápido usando Vite e React Router para roteamento SPA.</p>
<p>🔒 Autenticação e Cadastro: Páginas para login, cadastro e completar perfil (preparado para integração com backend).</p>
<p>🖼️ Galeria de Imagens: Visualização detalhada de produtos com múltiplas fotos.</p>
<p>📊 Listagem de Produtos: Páginas dedicadas para categorias, produtos relacionados e visualização individual.</p>
<p>🎨 Estilização Moderna: Utiliza Tailwind CSS para um design limpo e customizável.</p>

# 🛠️ Tecnologias Utilizadas
## Frontend
<img src="https://img.shields.io/badge/React-19.2.0-61DAFB?style=flat&amp;logo=react&amp;logoColor=white" alt="React">
- Biblioteca para construção de interfaces.
<img src="https://img.shields.io/badge/Vite-7.3.1-646CFF?style=flat&amp;logo=vite&amp;logoColor=white" alt="Vite">
- Ferramenta de build e desenvolvimento rápido.
<img src="https://img.shields.io/badge/React_Router_DOM-7.13.1-CA4245?style=flat&amp;logo=react-router&amp;logoColor=white" alt="React Router DOM">
- Roteamento para navegação SPA.
<img src="https://img.shields.io/badge/Tailwind_CSS-4.2.1-06B6D4?style=flat&amp;logo=tailwind-css&amp;logoColor=white" alt="Tailwind CSS">
- Framework CSS para estilização utilitária.
<img src="https://img.shields.io/badge/Axios-1.13.6-5A29E4?style=flat&amp;logo=axios&amp;logoColor=white" alt="Axios">
- Cliente HTTP para requisições (configurado para backend local).
<img src="https://img.shields.io/badge/React_Icons-5.6.0-000000?style=flat&amp;logo=react&amp;logoColor=white" alt="React Icons">
- Ícones para UI.
Ferramentas de Desenvolvimento
<img src="https://img.shields.io/badge/ESLint-8.x-4B32C3?style=flat&amp;logo=eslint&amp;logoColor=white" alt="ESLint">
- Linting para qualidade de código.
<img src="https://img.shields.io/badge/PostCSS-8.x-DD3735?style=flat&amp;logo=postcss&amp;logoColor=white" alt="PostCSS">
- Processamento de CSS.
<img src="https://img.shields.io/badge/Autoprefixer-10.x-DD3735?style=flat&amp;logo=autoprefixer&amp;logoColor=white" alt="Autoprefixer">
- Adição automática de prefixos CSS.
Futuro/Backend Planejado
<img src="https://img.shields.io/badge/Supabase-2.x-3ECF8E?style=flat&amp;logo=supabase&amp;logoColor=white" alt="Supabase">
- Para banco de dados, autenticação e API (não implementado ainda).

# ⚙️ Como Rodar o Projeto
##Siga os passos abaixo para configurar o ambiente e executar a Digital Store na sua máquina.

### Pré-requisitos
### Git (para clonar o código).
### Node.js (recomendado versão LTS, 18+) e um gerenciador de pacotes como npm ou yarn.
1. Clonar o Repositório
Abra o terminal e execute:

2. Instalar Dependências
Instale as bibliotecas necessárias:

3. Executar o Projeto
Inicie o servidor de desenvolvimento:

Após isso, abra o navegador http://localhost:5173/ para ver o projeto rodando.

# 🤝 Como Contribuir

### Contribuições são bem-vindas! Siga estes passos:

Faça um fork do projeto.
Crie uma branch para sua feature (git checkout -b feature/nova-funcionalidade).
Commit suas mudanças (git commit -m 'Adiciona nova funcionalidade').
Push para a branch (git push origin feature/nova-funcionalidade).
Abra um Pull Request.

# 📞 Contato
Autor: Felipe Castro<br>
Email: felipe.m.castro01@gmail.com 

# 📂 Estrutura do Projeto (Arquitetura Atômica)

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


