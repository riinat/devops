FROM node:16

EXPOSE 3000

WORKDIR /app

COPY . .

RUN npm install

RUN npm run build

RUN npm install -g serve

CMD ["serve", "-s", "-l", "5300", "build"]