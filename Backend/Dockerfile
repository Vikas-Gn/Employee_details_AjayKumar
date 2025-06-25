# Use Node.js base image
FROM node:18

# Create app directory
WORKDIR /app

# Install app dependencies
COPY package*.json ./
RUN npm install

# Copy the source code
COPY . .

# Expose backend port
EXPOSE 3051

# Start the server
CMD ["node", "server.js"]

