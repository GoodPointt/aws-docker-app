FROM node:latest

RUN mkdir -p /aws
WORKDIR /aws

COPY package.json /aws

RUN yarn

EXPOSE 1337/tcp

CMD ["yarn", "start"]