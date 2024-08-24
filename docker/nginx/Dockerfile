FROM nginx
RUN apt-get update
RUN apt-get install -y \
    bash \
    nano \
    less

COPY ./nginx.conf /etc/nginx/conf.d/default.conf