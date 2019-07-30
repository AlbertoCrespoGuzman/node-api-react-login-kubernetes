FROM node:10

WORKDIR /usr/src/app

COPY package*.json ./


# If you are building your code for production
# RUN npm ci --only=production

RUN npm install

COPY . .

EXPOSE 4444

CMD [ "node", "app.js" ]

