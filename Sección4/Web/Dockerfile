# Especify a base image
FROM node:alpine

# App Workdir
WORKDIR /usr/app

# Install some dependecies
COPY ./ ./
RUN npm install

# Default command
CMD ["npm", "start"]

# Comando para habilitar puertos
# ducker run -p 8080:8080 charliesd/simpleweb
