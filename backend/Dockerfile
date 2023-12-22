FROM node:latest
WORKDIR /app
COPY package*.json ./
RUN npm install -g @angular/cli
COPY ./app.js ./app.js
EXPOSE 3000
RUN npm install express
CMD ["node", "app.js"]


