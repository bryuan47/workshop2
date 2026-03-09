FROM nginx:1.21-alpine

# Remove default Nginx config
RUN rm /etc/nginx/conf.d/default.conf

# Copy your custom config
COPY nginx.conf /etc/nginx/conf.d/

EXPOSE 80

# Start Nginx in foreground
CMD ["nginx", "-g", "daemon off;"]