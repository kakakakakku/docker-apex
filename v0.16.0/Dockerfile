FROM alpine:3.9

RUN apk --no-cache add --virtual curl \
  && curl -sL https://github.com/apex/apex/releases/download/v0.16.0/apex_linux_amd64 -o /usr/local/bin/apex \
  && chmod +x /usr/local/bin/apex

ENTRYPOINT ["apex"]
