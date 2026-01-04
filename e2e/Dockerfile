FROM node:alpine

ENV CI=true
WORKDIR /usr/src/app

COPY . .

RUN npm install -g pnpm

RUN pnpm install

CMD ["pnpm", "test"]