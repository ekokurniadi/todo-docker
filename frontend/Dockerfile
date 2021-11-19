FROM node:16-alpine

ENV VUE_API_URL=http://localhost:8080

RUN mkdir /app

COPY . /app

RUN yarn --cwd /app install

CMD [ "yarn","--cwd","/app","serve" ]
