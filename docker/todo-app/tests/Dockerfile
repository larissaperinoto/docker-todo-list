FROM mjgargani/puppeteer:trybe1.0
WORKDIR /user/todo-app/tests
ADD node_modules.tar.gz ./
COPY . .
EXPOSE 3000
ENTRYPOINT [ "npm", "test" ]
