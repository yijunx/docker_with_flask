# Use the nginx image
FROM nginx

# Remove the detault conf
RUN rm /etc/nginx/conf.d/default.conf

# Replace with our own nginx.conf
COPY nginx.conf /etc/nginx/conf.d/
