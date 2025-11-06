# Use Node.js base image
FROM node:14-alpine

# Set working directory
WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy all frontend code
COPY . .

# Expose frontend port
EXPOSE 3000

# Start React app
CMD ["npm", "start"]
