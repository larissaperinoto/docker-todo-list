FROM node:14-alpine
WORKDIR /user/todo-app/back-end
ADD node_modules.tar.gz ./
COPY . .
EXPOSE 3001
ENTRYPOINT [ "npm", "start" ]