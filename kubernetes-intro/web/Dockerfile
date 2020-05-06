FROM nginx:latest

RUN usermod -u 1001 nginx && groupmod -g 1001 nginx

COPY conf/nginx.conf /etc/nginx/conf.d/default.conf
COPY app/* /app/

EXPOSE 8000