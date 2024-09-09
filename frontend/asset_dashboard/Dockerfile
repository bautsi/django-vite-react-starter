# Use an official Node.js runtime as the base image
FROM node:20

# Set the working directory inside the container
WORKDIR /app

# Copy package.json and package-lock.json into the container
COPY package*.json ./

# Install project dependencies
RUN npm install

# Copy the rest of the application files into the container
COPY . .

# Build the frontend with Vite
RUN npm run build

# Expose port 3000 or whichever port Vite is using
EXPOSE 3000

# Command to run the Vite preview server for production
CMD ["npm", "run", "dev","--","--host","0.0.0.0"]
