FROM alpine:3.8

RUN apk --no-cache add --virtual curl \
  && curl -sL https://github.com/apex/apex/releases/download/v1.0.0-rc2/apex_1.0.0-rc2_linux_amd64.tar.gz | tar zx -C /usr/local/bin \
  && chmod +x /usr/local/bin/apex

ENTRYPOINT ["apex"]
