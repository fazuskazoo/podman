# Use the official Node.js image as a base image
FROM node:18

# Create and set the working directory
WORKDIR /usr/src/app

# Copy package.json (no dependencies for client)
COPY package*.json ./

# Copy the client code
COPY . .

# Command to run the client application
CMD [ "node", "client.js" ]

