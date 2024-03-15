FROM nginx
LABEL nginxv="latest"

RUN echo "<h1>........ HELLO EVERYONE THIS PAGE HOSTED VIA DOCKER IMAGE CREATION ........</h1>" > /usr/share/nginx/html/index.html
EXPOSE 80

CMD nginx -DFOREGROUND
