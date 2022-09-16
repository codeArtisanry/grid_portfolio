FROM node:16.13.1-alpine as base
# FROM nikolaik/python-nodejs:python3.7-nodejs16 as base
# WORKDIR /run/nginx
WORKDIR /usr/src/app
COPY ./package*.json ./
# RUN apk add python3 py3-pip --verbose
RUN npm install --verbose
