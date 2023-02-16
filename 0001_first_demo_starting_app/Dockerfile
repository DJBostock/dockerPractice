FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD [ "node", "app.mjs"]

# docker build .
# docker run -p 3000:3000 <imageID>