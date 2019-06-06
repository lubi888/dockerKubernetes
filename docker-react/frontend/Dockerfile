FROM node:alpine as builder
WORKDIR '/app'
COPY package.json .
RUN npm install
COPY . .
RUN npm run build
# all to build the build folder in the working dir

FROM nginx:alpine
COPY --from=builder /app/build /usr/share/nginx/html
