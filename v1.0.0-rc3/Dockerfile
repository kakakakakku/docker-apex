FROM alpine:3.10.1

RUN apk --no-cache add --virtual curl \
  && curl -sL https://github.com/apex/apex/releases/download/v1.0.0-rc3/apex_1.0.0-rc3_linux_amd64.tar.gz | tar zx -C /usr/local/bin \
  && chmod +x /usr/local/bin/apex

ENTRYPOINT ["apex"]
