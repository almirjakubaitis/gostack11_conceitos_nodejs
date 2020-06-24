<h1 align="center">GOSTACK 11 DESAFIO 02</h1>
<h1 align="center">Conceitos Node.js :rocket:</h1>

<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />



## 💻 Sobre o Projeto
<h4>
  - Desafio 02: Conceitos Node.js
</h4>

<blockquote>
Essa será uma aplicação para armazenar repositórios do portfólio, que irá permitir a criação, listagem, atualização e remoção dos repositórios, e além disso permitir que os repositórios possam receber "likes".
</blockquote>

  

 ## 💻 Tecnologias
<h4>

   - Node.js

   - Javascript




### Aplication rotes


- **`POST /repositories`**: A rota deve receber `title`, `url` e `techs` dentro do corpo da requisição, sendo a URL o link para o github desse repositório. Ao cadastrar um novo projeto, ele deve ser armazenado dentro de um objeto no seguinte formato: `{ id: "uuid", title: 'Desafio Node.js', url: 'http://github.com/...', techs: ["Node.js", "..."], likes: 0 }`; Certifique-se que o ID seja um UUID, e de sempre iniciar os likes como 0.

- **`GET /repositories`**: Rota que lista todos os repositórios;

- **`PUT /repositories/:id`**: A rota deve alterar apenas o `title`, a `url` e as `techs` do repositório que possua o `id` igual ao `id` presente nos parâmetros da rota;

- **`DELETE /repositories/:id`**: A rota deve deletar o repositório com o `id` presente nos parâmetros da rota;

- **`POST /repositories/:id/like`**: A rota deve aumentar o número de likes do repositório específico escolhido através do `id` presente nos parâmetros da rota, a cada chamada dessa rota, o número de likes deve ser aumentado em 1;

## :memo: Licença

Esse projeto está sob a licença MIT. 
Veja o arquivo [LICENSE](.github/LICENSE.md) para mais detalhes.