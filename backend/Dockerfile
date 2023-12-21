FROM node:latest
WORKDIR /app
COPY package*.json ./
# RUN npm install
# Run npm clean install, including dev dependencies for @angular-devkit
# RUN npm ci
# Run npm install @angular/cli
RUN npm install -g @angular/cli
COPY . .
# EXPOSE 3000
RUN npm install express
CMD ["node", "app.js"]


