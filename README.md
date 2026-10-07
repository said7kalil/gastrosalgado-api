# GastroSalgado API

Backend (FastAPI + MongoDB) del panel clínico de drpablosalgado.com. Mismo código que los paneles de CardioBaus y del Dr. Julio Cascante.
No contiene credenciales: toda la configuración va en variables de entorno de Render
(MONGO_URL, DB_NAME=gastrosalgado, JWT_SECRET, SEED_USERS, SMTP_USER, SMTP_PASSWORD, CONTACT_RECIPIENT_EMAIL).
Cada cambio en la rama `main` se publica automáticamente en Render.
