FROM node:14
WORKDIR /user
EXPOSE 3001
ADD node_modules.tar.gz ./
COPY . .
ENTRYPOINT ["npm", "start"]

