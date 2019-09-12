#specify a base image
#FROM alpine
FROM node:alpine

WORKDIR /usr/app

COPY ./package.json ./

#Install some dependencies
COPY ./ ./

#copy things to the container
RUN npm install

#Default command
CMD ["npm", "start"]
