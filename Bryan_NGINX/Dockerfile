# docker run -d --name testing -p 8045:80 -v C:\data:/usr/share/nginx/html nginx:latest

FROM nginx:latest

RUN rm /usr/share/nginx/html/index.html

COPY /index.html /usr/share/nginx/html

EXPOSE 80
