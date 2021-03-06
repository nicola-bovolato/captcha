# Captcha

[![Test api](https://github.com/nicola-bovolato/captcha/actions/workflows/test-api.yaml/badge.svg?branch=master)](https://github.com/nicola-bovolato/captcha/actions/workflows/test-api.yaml)


Simple captcha service powered by modern technologies

### Run the app

 - `docker-compose up -d`
 - Visit [localhost](http://localhost)
 - Or visit the url specified in `docker-compose logs localtunnel`

The app is also hosted on [heroku](https://nb-captcha.herokuapp.com/)

## Technologies

 ### [Frontend](./frontend/)

  - `React`
  - `Bootstrap`
  - `Bootstrap Icons`

 ### [Backend](./api/)

  - `Typescript`
  - `TSyringe`
  - `Jest`
  - `Fastify`
  - `Redis`

 ### Putting it all together

  - `Docker`
  - `docker-compose`
  - `localtunnel`
