#specify a base image
FROM alpine

#create the working directory
WORKDIR /Users/Anshul/Docker

#install redis in alpine
RUN apk add --update redis

#start the redis server
CMD ["redis-server"]
