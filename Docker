# Use uma imagem base do Nginx
FROM nginx:alpine

# Copie os arquivos do projeto para o diretório padrão do Nginx
COPY . /usr/share/nginx/html

# Exponha a porta 80
EXPOSE 80

# Inicie o Nginx
CMD ["nginx", "-g", "daemon off;"]
