FROM php:8.1-alpine
WORKDIR /usr/src
COPY . .

EXPOSE 8888

CMD [ "php", "-S", "0.0.0.0:8888", "/usr/src/app/server.php" ]