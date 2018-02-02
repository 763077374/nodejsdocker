FROM node:onbuild

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY . /usr/src/app
EXPOSE 8081
CMD [ "npm", "start"]