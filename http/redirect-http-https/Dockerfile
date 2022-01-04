FROM nginx

COPY default.conf /etc/nginx/conf.d/default.conf
COPY passwordProtectedMedia.xml /usr/share/nginx/html/passwordProtectedMedia.xml
COPY nginx.conf /etc/nginx/vhost.d/localhost.conf
COPY nginx.conf /etc/nginx/vhost.d/127.0.0.1.conf
