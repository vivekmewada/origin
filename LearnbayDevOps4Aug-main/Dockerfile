FROM node:18

WORKDIR /app

COPY package*.json ./

RUN npm install --only=production

COPY . .

EXPOSE 3000

USER node

CMD ["npm", "start"]