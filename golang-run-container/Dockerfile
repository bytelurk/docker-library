FROM alpine:3.9

RUN apk add --no-cache \
		ca-certificates \
		tzdata \
		&& cp -r -f /usr/share/zoneinfo/Hongkong /etc/localtime \
		&& echo -ne "iamsee/golang-run-container Alpine Linux 3.9 image. (`uname -rsv`)\n" >> /root/.built
