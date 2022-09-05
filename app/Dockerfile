FROM  node:16

# create app directory
WORKDIR usr/src/app

# Install app dependencies
COPY package*.json ./

RUN npm install

# Bundle app source
COPY . .

EXPOSE 8080

# command to run when starting docker
CMD [ "node", "index.js"]