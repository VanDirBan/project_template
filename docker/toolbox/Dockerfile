FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python3 py3-pip
RUN pip install awscli --break-system-packages
CMD tail -f /dev/null
