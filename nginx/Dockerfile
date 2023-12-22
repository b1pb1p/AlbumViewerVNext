FROM nginx:1.25.3-alpine3.18

MAINTAINER Rick Strahl

# Copy custom nginx config
COPY ./nginx.conf /etc/nginx/nginx.conf
COPY ./wwwroot /usr/share/nginx/html

EXPOSE 80 443

ENTRYPOINT ["nginx"]
CMD ["-g", "daemon off;"]