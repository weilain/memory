FROM nginx
COPY nginx.conf /etc/nginx/nginx.conf
COPY webroot/* /usr/share/nginx/html/
RUN chmod -R a+r /usr/share/nginx/html/*
RUN mkdir /etc/nginx/logs
