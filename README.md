# Тема домашнего задания: Docker с проектом django rest api
Запускаем Docker и WSL
Запустите образ Docker: docker build -t django-rest-api .
Запустите контейнер: docker run -p 8000:8000 django-rest-api
Набираем в браузере: http://localhost:8000/api/sensors/
Убеждаемся, что страница по п.5 доступна