FROM nginx:latest

COPY ./conf.d /etc/nginx/conf.d

EXPOSE 80
EXPOSE 8888

CMD ["nginx", "-g", "daemon off;"]