# GoStack_02-Concepts_of_Node.js

**`This challenge objective was to create a node.js backend. The following should be completed:`** <br />

- **`POST /repositories`**: The route must receive `title`, `URL`, and `techs` inside of the request body. The URL must be the link to the Github of that repository. When registering a new project, it must be stored inside an object in the following format: `{id:" uuid ", title: 'Desafio Node.js', URL: 'http: //github.com / ...' , techs: ["Node.js", "..."], likes: 0} `; Make sure the ID is a UUID, and always start likes as 0.

- **`GET /repositories`**: The route that lists all repositories;

- **`PUT /repositories/:id`**: The route should only change the `title`, `URL` and `techs` of the repository that has the` id` equal to the `id` present in the route parameters;

- **`DELETE /repositories/:id`**: The route must delete a repository with the `id` present in the route parameters;

- **`POST /repositories/:id/like`**: The route must increase the number of likes from the specific repository chosen through the `id` param present in the route parameters, at each call of this route, the number of likes must be increased by 1; 

**`Every objective was reached! This a backend challenge so there aren't images for me to display.`** <br /> <br /> <br />


[Original challenge page.](https://github.com/rocketseat-education/bootcamp-gostack-desafios/blob/master/desafio-conceitos-nodejs/README.en.md) <br />
