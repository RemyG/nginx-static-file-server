FROM nginx:alpine
VOLUME ["/var/www/static"]
RUN rm -v /etc/nginx/nginx.conf
VOLUME ["/etc/nginx/nginx.conf"]
VOLUME ["/etc/nginx/conf.d"]
CMD ["nginx" ,"-g", "daemon off;"]