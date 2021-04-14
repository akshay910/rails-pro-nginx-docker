FROM nginx:latest

#RUN  rm  /etc/nignx/conf.d/default.conf

ENV RAILS_ROOT /var/www/app_name

COPY nginx.conf /etc/nginx/conf.d/

COPY . /etc/nginx
#RUN envsubst '$RAILS_ROOT' < /tmp/docker.nginx > /etc/nginx/conf.d/default.conf
