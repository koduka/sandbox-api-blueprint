FROM node:latest

WORKDIR /document

RUN npm install -g aglio --unsafe-perm

CMD [ "aglio", "--theme-variables", "slate", "-i", "index.md", "-s", "-h", "0.0.0.0"]