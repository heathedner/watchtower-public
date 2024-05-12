# Use the official Nginx image
FROM nginx:latest

# Copy custom configuration file from the host into the container
COPY nginx.conf /etc/nginx/nginx.conf

# Expose port 80 inside the container
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
