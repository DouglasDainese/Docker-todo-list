FROM node:14.21.2-alpine3.17
WORKDIR /back-end
EXPOSE 3001
ADD ./node_modules.tar.gz /back-end/
COPY . .
ENTRYPOINT [ "npm", "start" ]

