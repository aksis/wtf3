FROM alpine:3.14

RUN echo "TZif2UTCTZif2UTC" > /etc/localtime && echo "UTC0" >> /etc/localtime && echo "UTC" >  /etc/timezone

ENV LANG="C.UTF-8"

RUN apk add --no-cache --update --verbose ca-certificates netcat-openbsd curl

CMD [ "/bin/sh" ]
