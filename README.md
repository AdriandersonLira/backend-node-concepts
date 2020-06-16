<h1 align="center">
    <img alt="Backend Node" title="Backend Node" src="logo.svg" width="220px" />
</h1>

<p align="center">
  <a href="#-tecnologia">Tecnologia</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-comandos">Comandos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-contribuir">Como contribuir</a>
</p>

<p align="center">
 <img src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=7159c1&labelColor=000000" alt="PRs welcome!" />

 <img src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=7159c1&labelColor=000000" alt="PRs welcome!" />
</p>



<br>

<p align="center">
  <img alt="Ecoleta" src="starter/public/assets/ecoleta.png" width="100%">
</p>

## 🚀 Tecnologia

Projeto desenvolvido com a stack [Node.JS](https://nodejs.org/en/). É preciso fazer a instalação do yarn. mas pode ser feito com o npm também.

## 💻 Projeto

Nesse projeto contém os primeiros conceitos do Node.js. Dentre eles tem: 
- Métodos HTTP
  - GET - Buscar informações do back-end
  - POST - Criar informações no back-end
  - PUT/PATCH - Alterar uma informação no back-end
  - DELETE - Deletar uma informação no back-end

- Tipos de Parâmetros
  - Query Params - Filtros e Paginação
  - Route Params - Identificar recursos (Atualizar/Deletar)
  - Request Params - Conteúdo na hora de criar ou editar um recurso (JSON)

- Aplicação Funcional
- Middlewares
  - É um interceptador de requisições que pode:
    - Interromper totalmente a requisição.
    - Alterar dados da requisição.

## 👨🏻‍💻 Comandos

> Criação da pasta.
```
> mkdir backend
```
> Criação do package.json.
```
> yarn init -y
```
> Instalação do express.
```
> yarn add express
```
> Instalação do nodemon para executar o servidor e atulizar automaticamente.
```
> yarn add nodemon -D
```
> Abre o arquivo package.json e acrescenta:
```
>"scripts": {
    "start": "nodemon"
  },
```
> Agora inicia o servidor e ele dessa vez ele vai fazer o refresh automaticamente.
```
> yarn start
```

## 🤔 Como contribuir

- Faça um fork desse repositório;
- Cria uma branch com a sua feature: `git checkout -b minha-feature`;
- Faça commit das suas alterações: `git commit -m 'feat: Minha nova feature'`;
- Faça push para a sua branch: `git push origin minha-feature`.

Depois que o merge da sua pull request for feito, você pode deletar a sua branch.

---

Feito com ♥ by Adrianderson Lira 