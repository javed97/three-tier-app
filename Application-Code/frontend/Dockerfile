# Pull reactjs image
FROM node:14

# Define Working Directory
WORKDIR /app

# Copy package.json for installations
COPY package*.json ./

# Install packages
RUN npm install

# Copy the application code to the working dir
COPY . .

# RUN the application
CMD ["npm","start"]








