
# Use official node image as the base image
FROM node:latest as build

# Set the working directory
WORKDIR /app
RUN chown -R root:$(whoami) /app
RUN chmod -R 777 /app
# Add the source code to app
COPY . .

# Install all the dependencies
RUN npm install

# Generate the build of the application
CMD npm start



