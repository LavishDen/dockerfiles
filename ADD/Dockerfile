FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/LavishDen/dockerfiles/blob/main/README.md /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
