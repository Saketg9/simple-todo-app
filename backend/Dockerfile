FROM node:12

# Create app directory
RUN mkdir -p /usr/src/app

# Sets the newly created directory as the working directory.
WORKDIR /usr/src/app

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where available (npm@5+)
COPY package*.json ./

# Install the required packages in the image
RUN npm install

# Bundle app source
COPY . .

# Open the port on the container
EXPOSE 3000

# Run the command after creating the container
CMD [ "npm", "start" ]
