FROM nginx:latest

COPY nginx.conf /etc/nginx/nginx.conf
COPY certs/nginx.crt /etc/nginx/nginx.crt
COPY certs/nginx.key /etc/nginx/nginx.key
COPY .htpasswd /etc/nginx/.htpasswd
