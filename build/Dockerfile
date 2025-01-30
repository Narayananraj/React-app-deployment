# Step 1: Use the official Nginx image to serve the app
FROM nginx:alpine

# Step 2: Copy the contents of the current directory (build folder) to the Nginx html directory
COPY . /usr/share/nginx/html

# Step 3: Expose port 80 for HTTP traffic
EXPOSE 80

# Step 4: Run Nginx in the foreground to keep the container running
CMD ["nginx", "-g", "daemon off;"]

