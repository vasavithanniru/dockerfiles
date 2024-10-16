FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/daws-81s/notes/blob/main/session-43.txt /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]