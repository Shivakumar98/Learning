# Specify a base image
FROM node:alpine
WORKDIR /usr/shiva
COPY . .
# Install some depenendencies
RUN npm install

# Default command
CMD ["npm", "start"]