FROM nginx:alpine

COPY nginx.conf /etc/nginx/conf.d
EXPOSE 80

CMD ["/bin/sh", "-c", "exec nginx -g 'daemon off;';"]
WORKDIR /usr/share/nginx/html
