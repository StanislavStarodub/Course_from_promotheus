FROM nginx:stable

EXPOSE 8080

COPY nginx.conf /etc/nginx/conf.d/nginx.conf

COPY index.html /usr/share/nginx/html/index.html

STOPSIGNAL SIGQUIT

CMD ["nginx", "-g", "daemon off;"]