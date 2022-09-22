FROM node:14-alpine
EXPOSE 3001
ADD node_modules.tar.gz node_modules/
COPY . ./
ENTRYPOINT [ "npm", "start" ]