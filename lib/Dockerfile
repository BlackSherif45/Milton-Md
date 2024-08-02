FROM node:14

WORKDIR /app

*Copy the package.json and package-lock.json files to the container*
COPY package*.json ./

*Install dependencies*
RUN npm install

*Copy the rest of the application files to the container*
COPY . .

*Expose a port if your application requires it*
EXPOSE 8000

*Specify the command to run your application*
CMD [ "npm", "start" ]
