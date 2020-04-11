FROM nginx:1.16-alpine

RUN rm /etc/nginx/conf.d/default.conf

COPY nginx.dev.conf /etc/nginx/nginx.conf

EXPOSE 80
