#  from what image begin withs
FROM alpine

# download & install dependency
RUN apk add --update redis

# tell image what to do on startup
CMD [ "redis-server" ]


