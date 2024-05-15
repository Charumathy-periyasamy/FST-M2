#specify the base image
FROM alpine

# set the working directory
WORKDIR /usr/app

# install redis in alpine
RUN apk add --update redis

# Start the redis server , CMD is the command that will run as a first command when a server starts
CMD ["redis-server"] 

# we have build command which will create an image 
# we use -t to tag the image with our docker id
#
