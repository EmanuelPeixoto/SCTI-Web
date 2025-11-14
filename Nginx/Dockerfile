FROM nginx:alpine

# Instalar dependências necessárias
RUN apk add --no-cache bash

# Copiar configurações
COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 80 443

CMD ["nginx", "-g", "daemon off;"]
