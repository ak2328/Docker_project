from node:alpine

WORKDIR /usr/app

ADD ./package.json ./

RUN npm install

COPY ./ ./

CMD ["npm" , "start"]
