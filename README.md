# ReactNative_Francisco_Marquez
📌 MonumentApp
MonumentApp es una aplicación desarrollada en React Native con Expo que permite explorar y gestionar información sobre monumentos históricos. Los usuarios pueden agregar, editar y eliminar registros de manera sencilla.

🚀 Enlace al Repositorio de GitHub
🔗 https://github.com/franciscoMarquez7/ReactNative_Francisco_Marquez.git

🛠 Configuración de la Base de Datos
Para conectar la aplicación con la base de datos, usa los siguientes datos:

Nombre de la base de datos: ciudad_monumento
Usuario: root
Contraseña: test
Host: localhost
Puerto: 3306

📌 Requisitos para ejecutar el backend
Instalar Node.js y MySQL en tu sistema.
Clonar este repositorio:
git clone https://github.com/franciscoMarquez7/ReactNative_Francisco_Marquez.git
cd ReactNative_Francisco_Marquez
Instalar las dependencias del backend:
npm install
Crear la base de datos en MySQL con el siguiente comando:
CREATE DATABASE monumentos_db;
Configurar la conexión en el archivo .env:
env
DB_NAME=ciudad_monumento
DB_USER=root
DB_PASSWORD=test
DB_HOST=localhost
DB_PORT=3306
Iniciar el servidor backend:
npm start

📱 Configuración del Frontend (React Native con Expo)
Instalar Expo CLI si no lo tienes:
npm install -g expo-cli
Dentro de la carpeta del frontend, instalar dependencias:
npm install
Ejecutar Expo para probar la aplicación:
expo start

🔥 Tecnologías Utilizadas
Frontend: React Native con Expo, React Navigation, Gluestack UI
Backend: Node.js con Express
Base de datos: MySQL

⚠️ Notas Importantes
Asegúrate de que el servidor backend esté corriendo antes de iniciar la app.
La base de datos debe estar creada y accesible.
Si hay errores con Expo, limpia la caché ejecutando:
expo start --clear
Si el backend no responde, revisa los logs del servidor con:
npm run dev
💡 ¡Listo! Ahora puedes ejecutar MonumentApp y comenzar a gestionar monumentos! 🚀
