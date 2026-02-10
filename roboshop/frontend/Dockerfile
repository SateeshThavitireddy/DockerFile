FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY static /usr/share/nginx/html/
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]


# FROM nginx
# RUN rm -f /usr/share/nginx/html/*
# COPY ./static /usr/share/nginx/html/
# RUN rm -f vim /etc/nginx/nginx.conf
# COPY ./nginx.conf /etc/nginx/nginx.conf
# EXPOSE 80
# CMD ["nginx", "-g", "daemon off;"]