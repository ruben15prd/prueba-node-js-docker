FROM node:14

ENV NODEJS_WORK_DIRECTORY=/home/node/app

# Change to nodejs workspace
WORKDIR ${NODEJS_WORK_DIRECTORY}

RUN echo "Executing nodejs server"

ENTRYPOINT [ "node", "prueba/index.js" ]

