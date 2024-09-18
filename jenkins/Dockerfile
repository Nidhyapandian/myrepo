# Use the official Nginx base image
FROM nginx:alpine

# Copy the local index.html to the container's default Nginx HTML directory
COPY index.html /usr/share/nginx/html

# Expose port 80 to the outside world
EXPOSE 80

# Command to start Nginx when the container runs
CMD ["nginx", "-g", "daemon off;"]
