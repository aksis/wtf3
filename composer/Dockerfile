FROM wtf3/php

RUN wget -qO- https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

COPY ./docker-entrypoint.sh /docker-entrypoint.sh

RUN chmod +x /docker-entrypoint.sh

RUN mkdir -p /app

WORKDIR /app

ENTRYPOINT ["/docker-entrypoint.sh"]
