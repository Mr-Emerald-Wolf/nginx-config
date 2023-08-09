# Use an official NGINX image as the base image
FROM nginx:latest

# Copy your custom NGINX configuration file to the container
COPY nginx.conf /etc/nginx/nginx.conf

# Copy your application configuration to the conf.d directory
COPY default.conf /etc/nginx/conf.d/

# Expose port 80 for HTTP traffic
EXPOSE 80

# Start NGINX when the container runs
CMD ["nginx", "-g", "daemon off;"]

