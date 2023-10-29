FROM --platform=linux/amd64 nginx:alpine

# Копируем сгенерированный nginx.conf в образ
COPY nginx.conf /etc/nginx/
COPY nginx.conf /etc/nginx/conf.d/nginx.conf

# Открыть порт 80, чтобы обращаться к nginx
EXPOSE 80

# Запуск nginx в фоновом режиме
ENTRYPOINT ["nginx", "-g", "daemon off;"]
