FROM node:latest

RUN mkdir -p /aws
WORKDIR /aws

COPY package.json /aws

RUN npm install

EXPOSE 1337/tcp

CMD ["npm","run", "start"]