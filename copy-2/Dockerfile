FROM almalinux:9
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html 
ADD sample-1.tar /tmp/
CMD [ "sleep","1000" ]