FROM node:current-alpine

ENV APP_NAME=default

RUN mkdir /app
VOLUME /app
WORKDIR /app

RUN npm i -g @vue/cli

CMD vue create ${APP_NAME} --default
