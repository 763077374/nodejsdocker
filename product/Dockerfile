FROM node
#Create app directory
RUN mkdir -p /app
WORKDIR /app

#Install app dependencies
COPY . /app


RUN npm install

EXPOSE 8081

CMD ["npm","start"]