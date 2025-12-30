# 🚂 Estudos de Express.js (Módulo Intermediário)

Repositório dedicado ao aprendizado do framework **Express** para Node.js.
Este projeto é um "caderno de estudos" prático onde aplico conceitos fundamentais de backend.

## 🧠 O que foi aprendido e implementado

Neste repositório, explorei:
- **Configuração de Servidor:** Setup inicial com `app.listen`.
- **Roteamento:** Criação de rotas GET e POST.
- **Parâmetros de URL:** Captura de dados dinâmicos (`req.params`) para rotas como `/users/:id`.
- **Body Parser:** Configuração de middlewares (`express.urlencoded` e `express.json`) para ler dados enviados por formulários HTML via POST.
- **Arquivos Estáticos:** Uso do módulo `path` para servir páginas HTML.
- **Nodemon:** Configuração de ambiente de desenvolvimento.

## 🛠️ Tecnologias

- **Node.js**
- **Express**
- **Nodemon** (DevDependency)
- **HTML5** (Templates básicos)

## 📦 Como rodar este projeto

**1.** Clone o repositório.
**2.** Instale as dependências:
   npm install
**3.**Inicie o servidor:
   npm start
**4.**Acesse no navegador:
   http://localhost:3000
**5.**Teste de Formulário (POST):
   http://localhost:3000/users/add