FROM node:latest
# Create app directory
WORKDIR /usr/src/app
# Install app dependencies
COPY . .

RUN npm install --silent
# Copy app source code

RUN ls

#Expose port and start application
EXPOSE 3000
CMD ["npm", "start"]
