# Especify a base image
FROM node:alpine

# App Workdir
WORKDIR /usr/app

# Install some dependecies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]

# Comando para habilitar puertos
# docker run -p 8080:8080 charliesd/simpleweb
