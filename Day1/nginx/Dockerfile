FROM ubuntu

RUN apt update && apt install -y nginx

RUN service nginx start

CMD ["/etc/init.d/nginx","start"]
