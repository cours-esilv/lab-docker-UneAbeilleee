FROM jsuisuneabeille/nginx-frontend:latest
WORKDIR /usr/share/nginx/html
COPY entrypoint.sh /usr/share/nginx/html/entrypoint.sh
RUN chmod +x /usr/share/nginx/html/entrypoint.sh
CMD ["./entrypoint.sh"]
