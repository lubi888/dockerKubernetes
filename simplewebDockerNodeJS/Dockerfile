#base image
FROM node:alpine
# make a working directory
WORKDIR /usr/app
# imports from dir
COPY ./package.json ./
# install dependencies
RUN npm install
COPY ./ ./

# default command
CMD [ "npm", "start" ]

