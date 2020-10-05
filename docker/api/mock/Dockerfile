FROM node:latest

WORKDIR /mock

RUN npm install -g drakov

CMD [ "drakov", "-f", "./**/*.md", "--public", "--watch", "-p", "3001"]