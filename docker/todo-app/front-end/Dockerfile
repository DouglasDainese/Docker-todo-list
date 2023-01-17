FROM node:14.21.2-alpine3.17
WORKDIR /front-end
EXPOSE 3000
ADD ./node_modules.tar.gz /front-end/
COPY . .
ENTRYPOINT [ "npm", "start" ]

