#specify a base image 
FROM node:alpine 

#create a seperate folder structure for the project
WORKDIR /usr/app

#install deps
COPY ./package.json ./
RUN npm install 
COPY . .

#Default command for container run on start
CMD ["npm", "start"]