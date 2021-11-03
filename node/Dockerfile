FROM wtf3/core

RUN apk add --no-cache --update --verbose nodejs

COPY ./docker-entrypoint.sh /docker-entrypoint.sh

RUN chmod +x /docker-entrypoint.sh

RUN mkdir -p /app

WORKDIR /app

ENTRYPOINT ["/docker-entrypoint.sh"]
