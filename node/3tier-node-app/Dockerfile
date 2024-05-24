FROM node:20-alpine
WORKDIR /app
COPY ./app .
ENV MONGO_DB_USERNAME=idrees \
    MONGO_DB_PWD=idrees
RUN  npm install
EXPOSE 3000
CMD ["node", "server.js"]

