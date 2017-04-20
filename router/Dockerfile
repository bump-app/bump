FROM nginx:1.9
MAINTAINER bump-app <https://github.com/bump-app>

RUN rm /etc/nginx/conf.d/default.conf
COPY ./nginx.conf /etc/nginx/conf.d/bump.conf
