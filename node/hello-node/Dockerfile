FROM node
WORKDIR /usr/share/node/
COPY package* ./
RUN npm install
COPY . .
EXPOSE 3000
CMD ["node", "hello-node-updated.js"]

