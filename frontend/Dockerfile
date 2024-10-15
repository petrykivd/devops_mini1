FROM nginx:alpine

COPY nginx.conf /etc/nginx/nginx.conf

# Копіюємо HTML шаблон
COPY templates/index.html /usr/share/nginx/html/index.html

# Копіюємо config.json
COPY config.json /usr/share/nginx/html/config.json

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]