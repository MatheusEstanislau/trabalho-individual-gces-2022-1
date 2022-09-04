FROM node:lts-alpine
WORKDIR /frontend
COPY . .
RUN npm install
RUN npm run build
RUN npm install -g serve