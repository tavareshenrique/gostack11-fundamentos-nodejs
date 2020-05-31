<h1 align="center">
  <img alt="GoStack" src="./assets/gostack.png">
</h1>

<p align="center">
  <img alt="Last commit on GitHub" src="https://img.shields.io/github/last-commit/tavareshenrique/gostack11-fundamentos-node?color=7D40E7">
  <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%20?color=7D40E7">
  <img alt="Project top programing language" src="https://img.shields.io/github/languages/top/tavareshenrique/gostack11-fundamentos-node?color=7D40E7">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/tavareshenrique/gostack11-fundamentos-node?color=7D40E7">
  <img alt="GitHub license" src="https://img.shields.io/github/license/tavareshenrique/gostack11-fundamentos-node?color=7D40E7">
</p>

<p align="center">
  <a href="#information_source-content">⚙️ Iniciando</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-content">ℹ️ Conteúdo</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-technologies">🚀 Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-author">💻 Autor</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">📝 Licença</a>
</p>

<p align="center">
  A função desse desafio é criar uma aplicação para continuar treinando o que foi aprendido até agora no NodeJS junto ao TypeScript, utilizando o conceito de models, repositories e services no Bootcamp GoStack 11 da Rocketseat.
</p>

---

# :gear: Iniciando

```shell
# Clone o Repositório
git@github.com:tavareshenrique/gostack11-fundamentos-nodejs.git

## Baixe as dependencias
yarn

# Inicie o Projeto
yarn dev:server
```

---

# :information_source: Conteúdo

- [Transactions](#transactions)
  - [List All](#list-all-transactions)
  - [Create](#create-transactions)

---

# Transactions

## **List All** Transactions

List All Transactions.

* **URL**

  `/transactions`

* **Method:**

  `GET`

* **URL Params**

   **Required:**

    None

    **Optional:**

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:**

    ```json
    {
      "transactions": [
        {
          "id": "c12405f4-f8c3-402a-9a53-42fe24a97627",
          "title": "Salary",
          "value": 1000,
          "type": "income"
        },
        {
          "id": "bed84cf3-a2aa-4421-af27-4fc5dd1b588d",
          "title": "Home",
          "value": 200,
          "type": "outcome"
        }
      ],
      "balance": {
        "income": 1000,
        "outcome": 200,
        "total": 800
      }
    }
    ```

---

## **Create** Transactions

Create a Transaction.

* **URL**

  `/transactions`

* **Method:**

  `POST`

* **URL Params**

   **Required:**

    None

* **Data Params**

    ```json
    {
      "title": "Home",
      "value": 200,
      "type": "outcome"
    }
    ```

* **Success Response:**

  * **Code:** 200 <br />
    **Content:**

    ```json
    {
      "id": "bed84cf3-a2aa-4421-af27-4fc5dd1b588d",
      "title": "Home",
      "value": 200,
      "type": "outcome"
    }
    ```

---

# :rocket: Tecnologias

- [TypeScript](https://www.typescriptlang.org/)
- [ts-node-dev](https://github.com/whitecolor/ts-node-dev)
- [express](https://expressjs.com/pt-br/)
- [uuidv4](https://github.com/thenativeweb/uuidv4#readme)
- [eslint](https://eslint.org/)
- [prettier](https://prettier.io/)

---

# :computer: Autor

<table>
  <tr>
    <td align="center">
      <a href="http://github.com/tavareshenrique/">
        <img src="https://avatars1.githubusercontent.com/u/27022914?v=4" width="100px;" alt="Henrique Tavares"/>
        <br />
        <sub>
          <b>Henrique Tavares</b>
        </sub>
       </a>
       <br />
       <a href="https://www.linkedin.com/in/tavareshenrique/" title="Linkedin">@tavareshenrique</a>
       <br />
       <a href="https://github.com/tavareshenrique/gostack11-fundamentos-node/commits?author=tavareshenrique" title="Code">💻</a>
    </td>
    <td align="center">
      <a href="https://github.com/Rocketseat/">
        <img src="https://avatars0.githubusercontent.com/u/28929274?s=200&v=4" width="100px;" alt="Rocketseat"/>
        <br />
        <sub>
          <b>Rocketseat</b>
        </sub>
       </a>
       <br />
       <a href="https://www.linkedin.com/in/tavareshenrique/" title="Linkedin">@Rocketseat</a>
       <br />
       <a href="https://github.com/tavareshenriquegostack11-conceitos-reactjs/commits?author=tavareshenrique" title="Code">💻</a>
    </td>
  </tr>
</table>

---

# :memo: Licença

Este projeto está licenciado sob a licença MIT - consulte o arquivo [LICENSE.md](https://github.com/tavareshenrique/gostack11-fundamentos-node/blob/master/LICENSE.md) para obter detalhes.
