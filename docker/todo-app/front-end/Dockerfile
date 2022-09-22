FROM node:14-alpine
EXPOSE 3000
ADD node_modules.tar.gz node_modules/
COPY . ./
ENTRYPOINT [ "npm", "start" ]