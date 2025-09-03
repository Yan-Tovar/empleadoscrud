## 🔹 1. Clonar el repositorio
    git clone <URL-del-repositorio>
    cd <nombre-del-proyecto>
## 🔹 2. Instalar dependencias

    Entra a cada carpeta y ejecuta:

    Para el backend (Node.js / Express)
    cd backend   # o server
    npm install  # instala dependencias del backend
    Para el frontend (React)
    cd ../frontend   # o client
    npm install      # instala dependencias del frontend
## 🔹 3. Configurar variables de entorno

    Busca archivos como .env.example o README.md.

    Copia .env.example a .env y agrega tus configuraciones (puertos, conexión a DB, API keys, etc.).

    cp .env.example .env
## 🔹 4. Levantar los servidores

    Generalmente:

    Backend
    cd backend
    npm start   # o npm run dev (si usa nodemon)
    Frontend
    cd frontend
    npm start   # abre React en http://localhost:3000
🔹 5. Opcional: Levantar ambos con un solo comando

    Algunos repos tienen un script raíz (en el package.json principal) como:

    npm run dev