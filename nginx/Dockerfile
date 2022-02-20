FROM nginx:alpine
RUN apk add bash && \
    apk add vim && \
    apk add curl

COPY ./dump/user ./usr/user 

COPY ./nginx/default.conf /etc/nginx/conf.d/default.conf