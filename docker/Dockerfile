FROM nginx

WORKDIR /usr/share/nginx/html
COPY sample.html /usr/share/nginx/html

CMD cd /usr/share/nginx/html && sed -e s/Docker/"$AUTHOR"/ sample.html > index.html ; nginx -g 'daemon off;'
