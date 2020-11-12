FROM node:14.5.0

RUN mkdir /app
WORKDIR /app

COPY package*.json ./
COPY yarn.lock ./

RUN yarn

EXPOSE 3000

CMD ["yarn" , "dev"]
