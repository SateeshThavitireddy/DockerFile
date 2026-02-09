FROM nginx
RUN rm -f /usr/share/nginx/html/*
COPY ./static /usr/share/nginx/html/
RUN rm -f vim /etc/nginx/nginx.conf
COPY ./nginx.conf /etc/nginx/nginx.conf
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
