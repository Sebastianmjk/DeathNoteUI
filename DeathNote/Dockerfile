# Usa la imagen oficial de Nginx
FROM nginx:alpine

# Copia los archivos estáticos al directorio de Nginx
COPY DeathNote.html DeathNote.css DeathNote.js /usr/share/nginx/html/

# Copia la configuración personalizada de Nginx
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Expone el puerto 80
EXPOSE 80

# Comando para iniciar Nginx
CMD ["nginx", "-g", "daemon off;"]