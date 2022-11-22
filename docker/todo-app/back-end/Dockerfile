FROM node:14-alpine
WORKDIR /app
ADD node_modules.tar.gz .
COPY ./docker/todo-app/front-end/ /home/node/app
EXPOSE 3000
ENTRYPOINT ["npm", "start"]
