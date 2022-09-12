FROM node:14-alpine
WORKDIR /todo-app
COPY packge*.json ./
RUN npm install
ADD . .
EXPOSE 3001
CMD npm start