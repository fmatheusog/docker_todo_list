FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todoapp
COPY . .
ADD node_modules.tar.gz ./
ENTRYPOINT ["npm", "test"]