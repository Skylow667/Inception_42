FROM alpine:3.16.5

RUN	apk -U upgrade && apk add --no-cache vsftpd lftp shadow

COPY	conf /etc/vsftpd/vsftpd.conf

COPY    tools/start.sh /start.sh

CMD ["sh", "/start.sh"]

