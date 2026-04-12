# Imagen base
FROM node:18

# Directorio de trabajo dentro del contenedor
WORKDIR /app

# Copiar archivos
COPY package.json .

# Instalar dependencias
RUN npm install

# Copiar el resto
COPY . .

# Exponer puerto
EXPOSE 3000

# Comando de ejecución
CMD ["node", "app.js"]