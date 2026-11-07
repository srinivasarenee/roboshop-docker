FROM nginx:1.24.0
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/ngix/nginx.conf
COPY nginx.conf /etc/ngix/ngix.conf
COPY static/ /usr/share/nginx/html/