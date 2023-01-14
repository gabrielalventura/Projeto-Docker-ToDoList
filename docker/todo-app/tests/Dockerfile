FROM mjgargani/puppeteer:trybe1.0
WORKDIR /user
COPY . .
ADD node_modules.tar.gz .
ENTRYPOINT ["npm", "test"]