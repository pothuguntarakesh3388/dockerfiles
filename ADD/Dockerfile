FROM almalinux:9

RUN dnf install nginx -y
RUN rm -f /usr/share/nginx/html/index.html

ADD https://github.com/pothuguntarakesh3388/dockerfiles index.html /usr/share/nginx/html/index.html

CMD ["nginx", "-g", "daemon off;"]
