# Use latest Nginx image as base
FROM nginx:latest

# Remove default Nginx config file
RUN rm /etc/nginx/conf.d/default.conf

# Copy softy-pink-front-end to Docker file
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy Nginx config file to Docker image
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf