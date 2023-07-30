FROM nginx:1.21-alpine

# Remove default nginx configuration
RUN rm -rf /etc/nginx/conf.d

# Copy nginx configuration
COPY conf.d/ /etc/nginx/conf.d/
