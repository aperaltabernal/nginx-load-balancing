FROM nginx
WORKDIR /data
COPY index.html ./www/index.html
COPY nuevo.txt ./www/recurso/nuevo.txt
COPY ./recurso/index.html ./www/tmp/index.html
COPY nginx.conf /etc/nginx/nginx.conf