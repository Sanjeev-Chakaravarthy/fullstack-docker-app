# Use Node.js Alpine image
FROM node:14-alpine

# Set working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json ./
RUN npm install

# Copy the rest of backend files
COPY . .

# Expose backend port
EXPOSE 5001

# Start backend
CMD ["npm", "start"]