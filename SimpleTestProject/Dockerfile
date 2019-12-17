FROM node:10-alpine
WORKDIR /app
COPY App.config ./
RUN npm install
COPY . /app
CMD [ "npm", "test"]