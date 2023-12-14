FROM node:latest

RUN mkdir -p /aws/app
WORKDIR /aws

COPY package.json /aws
COPY app /aws/app

RUN npm install --omit=dev

EXPOSE 1337/tcp

CMD ["npm", "run", "start"]