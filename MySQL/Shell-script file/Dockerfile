FROM nginx
COPY my.sh /usr/local/bin/my.sh
RUN chmod +x /usr/local/bin/my.sh
EXPOSE 80
ENTRYPOINT ["/bin/bash","-c","/usr/local/bin/my.sh && nginx -g 'daemon off ;'"]
