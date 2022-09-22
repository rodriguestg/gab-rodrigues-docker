FROM mjgargani/puppeteer:trybe1.0
WORKDIR /usr/app
ADD node_modules.tar.gz node_modules/
COPY . ./
ENTRYPOINT [ "npm", "test" ]