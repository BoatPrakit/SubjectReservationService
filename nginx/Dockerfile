FROM docker.io/nginx:1.21.1-alpine

COPY nginx.conf /etc/nginx/conf.d/default.conf

COPY index.html /usr/share/nginx/html/

ENTRYPOINT [ "nginx", "-g", "daemon off;"]
