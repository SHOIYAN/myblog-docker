# Use a stable Node.js LTS version (like 16)
FROM node:16-alpine

# Set the working directory
WORKDIR /app

# Copy only package.json and package-lock.json first to install dependencies
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application files to the container
COPY . .

# Expose the port your app will run on
EXPOSE 3000

# Command to run the React app in development mode
CMD ["npm", "start"]
