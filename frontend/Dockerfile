FROM nginx:1.24.0
RUN rm -f /usr/share/nginx/html/index.html
RUN rm -f /etc/ngix/nginx.conf
#RUN rm -f /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/ngix/ngix.conf
COPY static /usr/share/nginx/html/