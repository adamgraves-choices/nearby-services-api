FROM node
RUN apt-get update && apt-get -y install git

WORKDIR /app

COPY package.json /app

RUN npm install

EXPOSE 3001

COPY . /app

CMD [ "npm", "start" ]
