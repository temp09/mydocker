#Use an existing docker image as a base
FROM alpine

# Dowload and install dependency
RUN apk add --update gcc
RUN apk add --update redis

# Tell the image what to do when it start as a container
CMD ["redis-server"]
