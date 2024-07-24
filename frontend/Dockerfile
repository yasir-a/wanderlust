FROM node:21

WORKDIR /frontend

COPY package*.json ./

RUN npm i

COPY . .

COPY .env.sample .env.local

EXPOSE 5173

CMD ["npm","run","dev", "--","--host"]
