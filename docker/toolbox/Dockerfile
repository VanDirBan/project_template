FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python3
RUN pip install awscli
RUN rm /var/cache/apk/*
CMD tail -f /dev/null
