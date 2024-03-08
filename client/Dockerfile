FROM node:alpine
WORKDIR /app
COPY package.json .
RUN npm install
COPY . .
COPY public /app/public
CMD ["npm", "start"]
