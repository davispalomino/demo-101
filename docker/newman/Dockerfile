FROM alpine:3.11.3
RUN apk update && apk add --no-cache nodejs nodejs-npm
RUN npm install -g newman@4.5.7 --silent
WORKDIR /etc/newman
ENTRYPOINT ["newman"]