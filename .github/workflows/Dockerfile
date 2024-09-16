# Usa la imagen oficial de Node.js 20 como base
FROM node:20-alpine3.20
# Establece el directorio de trabajo en /app
WORKDIR /app
# Copia el package.json y el package-lock.json al contenedor
COPY package*.json ./
# Instala las dependencias del proyecto
RUN npm install
# Copia el resto del código de la aplicación al contenedor
COPY . .
# Expone el puerto que utilizará la aplicación
EXPOSE 3000
# Establece las variables de entorno necesarias
ENV NODE_ENV=production
# Define el comando por defecto para ejecutar la aplicación
CMD ["npm", "start"]
