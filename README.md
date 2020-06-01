<h1 align="center">GOSTACK 11 CHALLENGE 02</h1>
<h1 align="center">Node.js concepts :rocket:</h1>

<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />



## 💻 About the Project
<h4>
  - Challenge 02: Node.js concepts
</h4>

<blockquote>
This application stores repositories in a portfolio, which will allow the creation, listing, update and removal of the repositories, and also allow the repositories to receive "likes".
</blockquote>
  

 ## 💻 Technologies
<h4>
   
   - Node.js

   - Javascript
</h4>




### Aplication rotes


- ** `POST / repositories` **: The route should receive` title`, `url` and` techs` within the body of the request, with the URL being the link to the github of this repository. When registering a new project, it must be stored inside an object in the following format: `{id:" uuid ", title: 'Desafio Node.js', url: 'http: //github.com / ...' , techs: ["Node.js", "..."], likes: 0} `; Make sure the ID is a UUID, and always start likes as 0.

- ** `GET / repositories` **: Route that lists all repositories;

- ** `PUT / repositories /: id` **: The route should only change the` title`, `url` and` techs` of the repository that has the `id` equal to the` id` present in the parameters of the route;

- ** `DELETE / repositories /: id` **: The route must delete the repository with the` id` present in the route parameters;

- ** `POST / repositories /: id / like` **: The route must increase the number of likes of the specific repository chosen through the` id` present in the route parameters, at each call of this route, the number of likes must be increased by 1;

## :memo: License

This project is under the MIT license. 
For more details visit: [LICENSE](.github/LICENSE.md).