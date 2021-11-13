#react-tensorflow

Si se descarga el repositorio con el Dockerfile, crear la imagen con:
`docker build -t react-sentiment-analysis .`

Luego, correr la webapp desde el contenedor de Docker con:
`docker run -it --rm -v ${PWD}:/usr/src/app -v /app/node_modules -p 3001:3000 -e CHOKIDAR_USEPOLLING=true react-tsflw:dev`

Descargar imagen de Docker Hub en https://hub.docker.com/r/vapaternina/react-sentiment-analysis con el comando: `docker pull vapaternina/react-sentiment-analysis`

Luego, correr la webapp desde el contenedor de Docker con:
`docker run -it --rm -v ${PWD}:/usr/src/app -v /app/node_modules -p 3001:3000 -e CHOKIDAR_USEPOLLING=true react-tsflw:dev`
