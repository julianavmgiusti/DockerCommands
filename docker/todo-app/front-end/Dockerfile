FROM node:14-alpine

WORKDIR /front-end

ADD node_modules.tar.gz .

COPY . .

EXPOSE 3000

RUN npm install


CMD ["npm", "start"]
