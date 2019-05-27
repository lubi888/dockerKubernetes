FROM node:alpine
WORKDIR /app
COPY package.json .
RUN npm install
# RUN redis server
COPY . .
CMD [ "npm", "start" ]
# CMD [ "redis server" ]