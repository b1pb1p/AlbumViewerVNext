FROM nginx:1.23.1-alpine

MAINTAINER Rick Strahl

# Copy custom nginx config
COPY ./nginx.conf /etc/nginx/nginx.conf
COPY ./wwwroot /usr/share/nginx/html

EXPOSE 80 443

ENTRYPOINT ["nginx"]
CMD ["-g", "daemon off;"]