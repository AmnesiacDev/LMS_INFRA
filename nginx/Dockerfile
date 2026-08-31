FROM nginx:alpine3.24

RUN rm /etc/nginx/conf.d/default.conf
COPY conf.d/ /etc/nginx/conf.d/

COPY certs/ /etc/nginx/certs/

EXPOSE 80
EXPOSE 443
