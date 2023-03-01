FROM node

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

EXPOSE 80

CMD ["node", "server.js"]

# Create The Image
# docker build .

# Run The Image
# docker run -p 80:80