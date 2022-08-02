FROM node:14

WORKDIR /todoapp/frontend

EXPOSE 3001

ADD node_modules.tar.gz .

COPY . .

CMD [ "npm", "start" ]