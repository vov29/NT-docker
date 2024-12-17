# Используем официальный образ nginx в качестве базового
FROM nginx:latest

# Удаляем стандартные файлы Nginx
RUN rm /usr/share/nginx/html/*

# Копируем Ваш HTML файл в нужную директорию
COPY index.html /usr/share/nginx/html/index.html

# Порт, который будет слушать Nginx
EXPOSE 80