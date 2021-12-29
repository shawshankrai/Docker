# Specify a base image
FROM node:alpine

WORKDIR /usr/app

# Install dependencies
COPY ./package.json ./
RUN npm install
# Copy everything else
COPY ./ ./

# Default command
CMD [ "npm",  "start"]