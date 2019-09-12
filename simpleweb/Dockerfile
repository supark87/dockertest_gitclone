#specify a base image
#FROM alpine
FROM node:alpine


#Install some dependencies
COPY ./ ./
RUN npm install

#Default command

CMD ["npm", "start"]
