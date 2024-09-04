
FROM node:18.9.1

WORKDIR /app

COPY package.json .
RUN npm install
EXPOSE 5173
COPY . .

CMD ["npm", "run", "dev"]
