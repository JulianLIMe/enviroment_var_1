# Description
This Repo was created to explain the use of environment variables, in the server.js file the server is executed using the configuration from config.js file, where the envirement where it is located, the host to use and the selected port are saved.
###
Here Not .env files are used, instead three different script are used to run this repo and simulate the environment variables file, this is posible by using the set command that allow setting variables in process.env (see package.json file, section scripts):

### npm start
Envirement variables have not been set here, this execute the server whit the next configs:

Envirement: default

Host: 127.0.0.1

PORT: 3000

### npm run dev
Here run the server by setting the following environment variables to simulete that it is in developer envirement:

Envirement: developer

Host: localhost

PORT: 4000

### npm run prod
Here run the server by setting the following environment variables to simulete that it is in production envirement:

Envirement: production

Host: 127.0.0.2

PORT: 5000