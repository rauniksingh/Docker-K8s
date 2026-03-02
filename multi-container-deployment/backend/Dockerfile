FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

ENV MONGODB_URL=mongodb+srv://raunik:388Raunik6@mongo-cloud.ptihnts.mongodb.net/mongo-cloud?retryWrites=true&w=majority

CMD ["npm", "start"]