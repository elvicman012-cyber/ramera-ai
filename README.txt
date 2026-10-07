RAMERA AI — instalación rápida

IMPORTANTE
Esta versión usa una API de IA real desde un backend local. La clave NO va dentro del HTML.

1) Instala Node.js LTS en tu PC.
2) Abre una terminal dentro de esta carpeta.
3) Ejecuta: npm install
4) Copia .env.example y renómbralo a .env
5) Abre .env y coloca tu clave en OPENAI_API_KEY.
6) Ejecuta: npm start
7) Abre: http://localhost:3000

Si tu cuenta no tiene disponible el modelo de ejemplo, cambia OPENAI_MODEL por un modelo que aparezca disponible en tu proyecto.

La interfaz guarda conversaciones en localStorage del navegador. El backend envía los últimos 30 mensajes a la API.

NO pongas tu API key en index.html ni publiques el archivo .env.
