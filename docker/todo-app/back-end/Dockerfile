FROM node:14-alpine
WORKDIR /todo-app/back-end
ADD node_modules.tar.gz ./
EXPOSE 3001
COPY . .
ENTRYPOINT [ "npm", "start" ]