FROM node:latest

RUN npm install -g easymock

RUN mkdir /var/easymock
WORKDIR /var/easymock
COPY json /var/easymock

EXPOSE 80

ENTRYPOINT ["easymock", "-p", "80"]