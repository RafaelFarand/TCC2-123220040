# Gunakan Node.js sebagai base image
FROM node:18-alpine

# Atur working directory
WORKDIR /app

# Salin package.json dan package-lock.json terlebih dahulu
COPY package*.json ./

# Install dependencies
RUN npm install

# Salin semua file proyek ke dalam container
COPY . .

# Ekspos port yang digunakan oleh server
EXPOSE 5000

# Perintah untuk menjalankan server
CMD ["node", "server.js"]
