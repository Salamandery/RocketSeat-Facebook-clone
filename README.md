<div align="center">
  <img src="https://i.imgur.com/KDIDiSE.png" alt="Logo Facebook Clone" width="120" />
  
  # Facebook Clone 🚀
  
  [![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
  [![React](https://img.shields.io/badge/React-16.8.6-61dafb?logo=react)](https://reactjs.org/)
  [![Build with Webpack](https://img.shields.io/badge/build-webpack-4.35.0-blue?logo=webpack)](https://webpack.js.org/)
</div>

---

<p align="center">
  Um clone simplificado da interface do Facebook, desenvolvido com <b>ReactJS</b>, focado em componentização, boas práticas e estilização moderna.
</p>

---

## 📑 Sumário
- [Demonstração](#demonstração)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Padrões e Estrutura](#padrões-e-estrutura)
- [Como Rodar o Projeto](#como-rodar-o-projeto)
- [Estrutura de Pastas](#estrutura-de-pastas)
- [Autor](#-autor)
- [Licença](#licença)

---

## 🖼️ Demonstração

<p align="center">
  <img src="assets-desafio/facebook.png" alt="Demonstração da aplicação" width="80%" />
</p>

---

## 🚀 Tecnologias Utilizadas

- <b>React</b> 16.8.6
- <b>PropTypes</b> para tipagem de props
- <b>Webpack</b> 4 (build e dev server)
- <b>Babel</b> (transpile ES6+ e JSX)
  - @babel/preset-env
  - @babel/preset-react
  - @babel/plugin-proposal-class-properties
- <b>CSS Loader, Style Loader, File Loader</b> (webpack)
- <b>Google Fonts Material Icons</b> (via CSS import)

---

## 🧩 Padrões e Estrutura

- <b>Componentização</b>: Separação clara entre Header, PostList, PostItem e comentários.
- <b>Stateful e Stateless Components</b>: PostList é um componente de classe com estado; PostItem e Header são funcionais.
- <b>Props</b>: Comunicação entre componentes via props.
- <b>Estilização</b>: CSS modularizado em <code>App.css</code>, incluindo reset e responsividade básica.
- <b>Imagens e ícones</b>: Ícones do Material Icons via Google Fonts.

---

## ⚙️ Como Rodar o Projeto

1. <b>Clone o repositório:</b>
   ```bash
   git clone <url-do-repo>
   cd RocketSeat-Facebook-clone
   ```
2. <b>Instale as dependências:</b>
   ```bash
   yarn install
   # ou
   npm install
   ```
3. <b>Inicie o servidor de desenvolvimento:</b>
   ```bash
   yarn dev
   # ou
   npm run dev
   ```
   O app estará disponível em <b>http://localhost:8080</b>.

4. <b>Build para produção:</b>
   ```bash
   yarn build
   # ou
   npm run build
   ```
   O bundle será gerado em <code>/public/bundle.js</code>.

---

## 📁 Estrutura de Pastas

```
RocketSeat-Facebook-clone/
├── src/
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── components/
│       ├── Header.js
│       ├── PostList.js
│       └── PostItem.js
├── public/
│   ├── index.html
│   └── bundle.js
├── assets-desafio/ (imagens e layout)
├── webpack.config.js
├── babel.config.js
├── package.json
└── README.md
```

---

## 👤 Autor
by **Rodolfo M. F. Abreu**
<p align="center">
  <sub>Desenvolvido para o desafio GoStack 🚀</sub>
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/Feito%20com%20%E2%9D%A4%20por-Rocketseat-blueviolet" />
</p>


---

<div align="center">
  <sup>Este projeto está sob a licença MIT. Veja o arquivo <a href="LICENSE">LICENSE</a> para mais detalhes.</sup>
</div>


