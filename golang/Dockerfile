FROM golang:alpine

RUN apk add --no-cache \
		git \
		openssh \
		tzdata \
		make \
		&& cp -r -f /usr/share/zoneinfo/Hongkong /etc/localtime \
		&& echo -ne "Alpine Linux 3.9 image. (`uname -rsv`)\n" >> /root/.built 
		