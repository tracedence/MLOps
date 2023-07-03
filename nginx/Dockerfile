# Base image
FROM nginx:latest

# Remove the default Nginx configuration
# RUN rm /etc/nginx/conf.d/default.conf

# Copy the custom Nginx configuration
# COPY nginx.conf /etc/nginx/conf.d/
copy ./nginx.conf /etc/nginx/nginx.conf

# Expose Nginx port
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]