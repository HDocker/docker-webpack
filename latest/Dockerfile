FROM node
MAINTAINER Justin Firth <jmfirth@gmail.com>

RUN npm install -g webpack webpack-dev-server npm-cache yarn

RUN yarn config set registry https://registry.npm.taobao.org --global
RUN yarn config set disturl https://npm.taobao.org/dist --global



VOLUME /app

EXPOSE 3000

WORKDIR /app
