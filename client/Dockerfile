FROM node:latest 
MAINTAINER Jhonata Junior
COPY . /var/www
ENV PORT=300
WORKDIR /var/www
RUN npm install
ENTRYPOINT npm start 
EXPOSE 3000 