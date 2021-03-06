# Negratec in ReactJS

This project is a copy from [negratec.github.io](http:////negratec.github.io) but developed with React.
So far the intention for this repo is just for learning.

## Learning Goals

- Docker
- ReactJS
- Redux
- Node/Express
- Logging and monitoring - Sumologic/Datadog

## Starting

1. Install [Docker Toolbox](https://www.docker.com/products/docker-toolbox)
2. Copy the project from github to your machine: `$ git clone git@github.com:NegraTec/negra-react.git`
3. In the project folder run `docker build -t negra-react .`
4. In the project folder run `docker run  -p 3000:3000 -t negra-react npm run start`
5. Access in your browser http://localhost:3000

## Tests

...

## Next steps

* [x] Make Express serve a React page.

     * [x] Use of webpack
 
     * [x] Use of Babel

* [x] Make Docker bundle the React code.
* [ ] Create a first version of the main page.
* [ ] Run tests by docker.
* [ ] Create tests for React components.
* [ ] Add redux.
* [ ] Create tests for redux.
* [ ] Add a logs strategy.
* [ ] Integrate with sumologic and datadog.

## Some interesting reading

https://facebook.github.io/react/docs/installation.html

https://camjackson.net/post/9-things-every-reactjs-beginner-should-know

https://www.codementor.io/tamizhvendan/tutorials/beginner-guide-setup-reactjs-environment-npm-babel-6-webpack-du107r9zr

https://medium.com/@housecor/react-stateless-functional-components-nine-wins-you-might-have-overlooked-997b0d933dbc#.cqt3kxptl
