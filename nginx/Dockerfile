FROM nginx:1.17
MAINTAINER alexey.i.egorov@megafon.ru
COPY nginx.conf /etc/nginx/conf.d/default.conf
WORKDIR /ets/nginx
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]