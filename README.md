# Sentiment Analysis con Tensorflow & React

## Vía repositorio

Usar los siguientes comandos en orden:
1. `git clone https://github.com/vapaternina/react-tensorflow.git`
2. `docker build -t react-sentiment-analysis .`
3. `docker run -it --rm -v ${PWD}:/usr/src/app -v /app/node_modules -p 3001:3000 -e CHOKIDAR_USEPOLLING=true react-sentiment-analysis:dev`
4. Ir a http://localhost:3001

## Vía Docker Hub ( https://hub.docker.com/r/vapaternina/react-sentiment-analysis ):
1. `docker pull vapaternina/react-sentiment-analysis`
2. `docker run -it --rm -v ${PWD}:/usr/src/app -v /app/node_modules -p 3001:3000 -e CHOKIDAR_USEPOLLING=true vapaternina/react-sentiment-analysis:v1.0.0`
3. Ir a http://localhost:3001


Proyecto original: https://github.com/manfye/tfjs-react
