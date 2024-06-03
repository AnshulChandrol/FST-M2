#specify a base image
FROM node:18-alpine

#create the working directory
WORKDIR /usr/app

#copy package.json into the container
COPY package.json /usr/app

#install required dependency
RUN npm install

#copy other files
COPY ./ /usr/app

#start the NodeJS Server
CMD ["npm","start"]