# 📘 Curso JavaScript e TypeScript do básico ao avançado

Exercícios e projetos que desenvolvi durante o curso [JavaScript e TypeScript do básico ao avançado - JS + TS](https://www.udemy.com/course/curso-de-javascript-moderno-do-basico-ao-avancado/), de Luiz Otávio Miranda (Udemy, 146 h), do JavaScript moderno até Node.js e React. Outros projetos do curso estão em repositórios próprios: [escola-api](https://github.com/LucianoMachadoS/escola-api), [React-Lista-Tarefa](https://github.com/LucianoMachadoS/React-Lista-Tarefa), [typescript-react-pomodoro](https://github.com/LucianoMachadoS/typescript-react-pomodoro) e [blog-strapi](https://github.com/LucianoMachadoS/blog-strapi).

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=flat&logo=webpack&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)

## ⭐ Destaques

| Projeto | O que é | Tecnologias |
|---|---|---|
| [`ProjetoAgenda`](./JavaScriptAvancado/ProjetoAgenda) | Agenda de contatos com cadastro, login e CRUD de contatos | Node, Express, MongoDB/Mongoose, EJS, sessões, bcrypt |
| [`gerador de senhas`](./JavaScriptAvancado/Javascript%20Tooling%20ES6/gerador%20de%20senhas) | Gera senhas com as opções escolhidas pelo usuário | ES6 Modules, Webpack, Babel |
| [`geracpfn`](./JavaScriptAvancado/Javascript%20Tooling%20ES6/geracpfn) | Gerador e validador de CPF | Classes, Webpack |
| [`react-base`](./React/react-base) | Projeto base com rotas | React, React Router |

## 📂 Organização

```
├── JavaScriptAvancado/
│   ├── Orientação a Objeto/
│   ├── Javascript Tooling ES6/   # Webpack, Babel, módulos
│   ├── Node Express/             # Express, MongoDB
│   ├── ProjetoAgenda/            # projeto completo MVC
│   └── api-rest/
├── AulasNovas/                   # Fetch API e Axios
├── ajax/
└── React/
```

## 🚀 Como rodar um projeto

Cada pasta com `package.json` é independente:

```bash
cd "JavaScriptAvancado/ProjetoAgenda"
npm install
npm start
```

O `ProjetoAgenda` precisa de um `.env` com a string de conexão do MongoDB (`CONNECTIONSTRING=...`).

---
Feito por [Luciano Machado](https://github.com/LucianoMachadoS)
