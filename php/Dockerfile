FROM wtf3/core

RUN apk add --no-cache --update --verbose php php-json php-phar php-iconv php-mbstring php-openssl php-curl php-intl php-tokenizer php-dom php-simplexml php-xml php-xmlreader php-xmlwriter php-xmlrpc php-fileinfo php-ctype

COPY ./docker-entrypoint.sh /docker-entrypoint.sh

RUN chmod +x /docker-entrypoint.sh

RUN mkdir -p /app

WORKDIR /app

ENTRYPOINT ["/docker-entrypoint.sh"]
