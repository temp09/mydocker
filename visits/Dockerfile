#Use an existing docker image as a base
FROM node:alpine

# Dowload and install dependency
COPY ./ ./
RUN npm install

# Tell the image what to do when it start as a container
CMD ["npm", "start"]