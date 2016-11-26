FROM nginx:1.11.5

RUN echo "daemon off;" >> /etc/nginx/nginx.conf

# Remove the default Nginx configuration file
ADD sites-enabled/ /etc/nginx/sites-enabled/