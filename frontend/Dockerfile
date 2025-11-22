# Use Node.js Alpine image
FROM node:14-alpine

WORKDIR /app

# Copy package.json and install dependencies
COPY package.json ./
RUN npm install

# Copy the rest of the React app
COPY . .

# Expose frontend port
EXPOSE 3000

CMD ["npm", "start"]