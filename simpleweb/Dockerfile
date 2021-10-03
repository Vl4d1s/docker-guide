# Specify a base image for
FROM node:alpine

WORKDIR /usr/app

COPY ./ ./

# Install some dependencies
RUN npm install

# Default command
CMD ["npm", "start"]

# Build command + image tagging
# docker build -t vladismarkin/simpleweb .
