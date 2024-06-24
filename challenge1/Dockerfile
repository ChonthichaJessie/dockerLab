# Use NGINX Alpine as base image
FROM nginx:alpine

# Copy the contents of the local 'public' directory to NGINX's default public folder
COPY public /usr/share/nginx/html

# Expose port 80 to the Docker host, so external connections can access our site
EXPOSE 80

# Default command to start NGINX when a container is started
CMD ["nginx", "-g", "daemon off;"]