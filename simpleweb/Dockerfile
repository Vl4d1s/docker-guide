# Specify a base image for
FROM node:alpine

WORKDIR /usr/app

COPY ./package.json ./

# Install some dependencies
RUN npm install

COPY ./ ./

# Default command
CMD ["npm", "start"]

# Build command + image tagging:
# docker build -t vladismarkin/simpleweb .

# Running command + port mapping:
# docker run -p 8080:8080 vladismarkin/simpleweb

# Opening shell's container:
# docker run -it vladismarkin/simpleweb sh

# Creating new shell proces:
# docker exec -it 8eaafc5a8c40 sh