# Pull nodejs image
FROM node:14

# Make work directory
WORKDIR /app

# Copy code
COPY package*.json ./

# Install packages
RUN npm install

# Copy the application code
COPY . .

# Run applicaton
CMD ["node","index.js"]
