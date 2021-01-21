FROM node:latest
# Create app directory
WORKDIR /usr/src/app
# Install app dependencies
#COPY package*.json ./
COPY . .

RUN npm install
# Copy app source code

RUN ls
#Expose port and start application
EXPOSE 8080
CMD [ "npm", "start" ]
