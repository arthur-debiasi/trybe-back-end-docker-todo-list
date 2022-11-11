FROM node:14-alpine AS todolist

WORKDIR /home/arthur/trybe-projects/back-end/sd-024-b-project-docker-todo-list/docker/todo-app/back-end

EXPOSE 3001

ADD node_modules.tar.gz .

COPY . .

RUN npm start
