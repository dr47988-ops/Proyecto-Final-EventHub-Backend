# EventHub - Backend

Backend del proyecto final EventHub.

## Tecnologías
- Node.js
- Express
- MongoDB
- JWT
- Google OAuth
- Jest

## Funcionalidades implementadas

- Registro e inicio de sesión.
- Autenticación con Google.
- Verificación de correo electrónico.
- Recuperación de contraseña.
- Autenticación mediante JWT.
- Roles de usuario y administración de usuarios.

## Requisitos

- Node.js y npm.
- Acceso a una base de datos MongoDB.
- Variables de entorno configuradas.

## Instalación

1. Clonar el repositorio:

git clone https://github.com/dr47988-ops/Proyecto-Final-EventHub-Backend.git

2. Entrar a la carpeta:

cd Proyecto-Final-EventHub-Backend

3. Instalar dependencias:

npm install

4. Crear el archivo .env utilizando .env.example como referencia.

5. Configurar las variables necesarias:

PORT=3000
NODE_ENV=development
MONGODB_URI=
JWT_SECRET=
JWT_REFRESH_SECRET=
GOOGLE_CLIENT_ID=
FRONTEND_URL=http://localhost:5173
SMTP_HOST=
SMTP_PORT=587
SMTP_USER=
SMTP_PASSWORD=
SMTP_FROM=

Las credenciales reales deben obtenerse de la persona encargada del proyecto. No deben subirse a GitHub.

## Ejecutar el servidor

node src/server.js

El servidor utiliza por defecto:

http://localhost:3000

## Ejecutar pruebas

npm test

Resultado comprobado: 29 pruebas exitosas en 2 suites.

## Frontend

Repositorio:
https://github.com/dr47988-ops/Proyecto-Final-EventHub-Frontend

El frontend se ejecuta por separado, normalmente en http://localhost:5173.

## Trabajo colaborativo

Cada integrante debe crear su propia rama para desarrollar nuevas funcionalidades.

No modificar directamente la rama main sin revisar los cambios.

No subir archivos .env, contraseñas ni claves privadas.
