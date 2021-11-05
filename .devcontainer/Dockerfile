FROM node:16.13.0-alpine

USER root
# Installing Angular
RUN apk update && npm install -g @angular/cli
# Installing Git
RUN apk add git
USER node