FROM nginx:alpine

# Копируем сгенерированный nginx.conf в образ
COPY nginx.conf /etc/nginx/

# Открыть порт 80, чтобы обращаться к nginx
EXPOSE 80

# Запуск nginx в фоновом режиме
CMD ["nginx", "-g", "daemon off;"]
