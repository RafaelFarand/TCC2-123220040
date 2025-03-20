# Gunakan Nginx sebagai base image
FROM nginx:latest

# Salin file frontend ke dalam direktori Nginx
COPY ./dist /usr/share/nginx/html

# Jalankan Nginx (ini sudah default di base image)
CMD ["nginx", "-g", "daemon off;"]
