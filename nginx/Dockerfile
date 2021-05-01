# Use the Python3.7.2 image
FROM nginx

# Remove default nginx config
RUN rm /etc/nginx/conf.d/default.conf

# Replace with our own nginx config
COPY nginx.conf /etc/nginx/conf.d/