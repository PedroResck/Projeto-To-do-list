FROM node:14-alpine AS todofrontend
WORKDIR /app
EXPOSE 3000
ADD node_modules.tar.gz ./
COPY . .
ENTRYPOINT [ "npm", "start" ]