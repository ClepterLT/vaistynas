FROM nginx:stable

# Remove default config
RUN rm /etc/nginx/conf.d/default.conf

#Copy new config
COPY nginx.conf /etc/nginx/conf.d/default.conf