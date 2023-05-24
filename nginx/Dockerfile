FROM nginx

RUN apt update
RUN apt upgrade -y
RUN rm /etc/nginx/conf.d/default.conf
COPY conf.d/ /etc/nginx/conf.d
