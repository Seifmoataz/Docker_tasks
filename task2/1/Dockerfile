#base image
FROM node:16

#Working directory
WORKDIR /apptest

#copying and running dependencies
COPY package.json .
RUN npm install

#copying app
COPY . .

#expose ports
EXPOSE 3000

#Command
CMD [ "node","app.js" ]

