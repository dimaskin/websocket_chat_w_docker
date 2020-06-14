FROM node:10
ADD . /usr/src/app
WORKDIR /usr/src/app
ENV PATH="/usr/src/app/node_modules/.bin/:${PATH}"
RUN yarn
RUN yarn run build
CMD yarn start
EXPOSE 3000