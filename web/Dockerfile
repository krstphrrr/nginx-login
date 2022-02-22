FROM node:alpine

RUN apk add bash && \
    apk add vim && \
    apk add curl

WORKDIR /app

# COPY ./web/package.json ./
# COPY ./web/package-lock.json ./
# COPY ./web/tsconfig.json ./
# COPY ./web/src ./
COPY ./web /app

RUN npm i

CMD ["npm", "start"]