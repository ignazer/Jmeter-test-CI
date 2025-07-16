FROM node:18-alpine
WORKDIR /app
COPY package.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD ["npm", "start"]

#Explanation:
# This Dockerfile sets up a Node.js application in a Docker container.  
# It uses the Node.js 18 Alpine image for a lightweight environment.
# The working directory is set to /app, where the application files will be copied.

# It installs the dependencies defined in package.json, copies the rest of the application files,
# exposes port 3000 for the application, and finally runs the application using npm start.
# The application is named "dummy-app" to reflect its purpose as a placeholder or example application.
