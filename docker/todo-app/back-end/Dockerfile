FROM node:14
WORKDIR /user/todo-app/back-end
COPY packge*.json ./
RUN npm install
ADD node_modules.tar.gz ./
COPY . .
EXPOSE 3001
CMD npm start