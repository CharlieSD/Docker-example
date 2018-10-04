# Especify a base image
FROM node:alpine

# Install some dependecies
COPY ./ ./
RUN npm install

# Default command
CMD ["npm", "start"]

# Comando para habilitar puertos
# ducker run -p 8080:8080 charliesd/simpleweb
