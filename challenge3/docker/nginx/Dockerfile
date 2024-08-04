# Dockerfile for nginx service
FROM nginx:latest

# Remove the default nginx configuration file
RUN rm /etc/nginx/conf.d/default.conf

# Copy the custom nginx configuration file
COPY docker/nginx/nginx.conf /etc/nginx/conf.d/default.conf