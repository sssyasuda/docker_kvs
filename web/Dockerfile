From nginx:1.17.5-alpine
COPY ./start.sh /usr/local/bin/start.sh
RUN chmod +x /usr/local/bin/start.sh
COPY ./nginx.tpl /etc/nginx/nginx.tpl
COPY ./html/ /usr/share/nginx/html/
ENV PORT 80
ENV APP_SERVER "http://127.0.0.1:8080"
<<<<<<< HEAD
CMD ["sh","/usr/local/bin/start.sh"]
=======
CMD ["sh","/usr/local/bin/start.sh"]
>>>>>>> 0b23400ef73ef78329de74e1fc4efa8fc0be819c
