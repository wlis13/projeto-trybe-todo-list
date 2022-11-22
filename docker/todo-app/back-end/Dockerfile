FROM node:14-alpine
WORKDIR /app
ADD node_modules.tar.gz .
COPY ./docker/todo-app/back-end/ /home/node/app
EXPOSE 3000
CMD ["npm", "start"]
