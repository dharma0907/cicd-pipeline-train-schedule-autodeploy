FROM node:carbon
WORKDIR /usr/src/app
COPY trainapp/package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "npm", "start" ]
