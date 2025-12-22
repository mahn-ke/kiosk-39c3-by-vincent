FROM node:25-alpine

WORKDIR /app
COPY ./wwwroot /app

RUN apk add --no-cache curl \
    && npm i http-server

CMD ["npx", "http-server", "--port=3000"]
