FROM node:16.16.0

WORKDIR /backend
RUN npm i -g @nestjs/cli
COPY package.json .
RUN npm install

COPY . .

CMD npm run start
