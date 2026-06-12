# 🚀 Nombre del Proyecto

> Descripción breve del proyecto: qué hace, para quién y por qué existe.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

---

## 🛠 Tech Stack

**Frontend**
- Framework: React / Next.js / Vue
- Estilos: Tailwind CSS / SCSS
- State: Redux / Zustand / Pinia

**Backend**
- Runtime: Node.js / Python / Go
- Framework: Express / FastAPI / Gin
- Base de datos: PostgreSQL / MongoDB

**Infraestructura**
- Contenedores: Docker + Docker Compose
- CI/CD: GitHub Actions
- Deploy: Vercel / Railway / AWS

## ⚡ Instalación y uso

### Requisitos previos
- Node.js >= 18
- Docker (opcional)
- Variables de entorno configuradas (ver `.env.example`)

### Desarrollo local

```bash
# 1. Clonar el repositorio
git clone https://github.com/tu-usuario/nombre-proyecto.git
cd nombre-proyecto

# 2. Instalar dependencias
npm install           # raíz (monorepo) o frontend
cd backend && npm install

# 3. Configurar variables de entorno
cp .env.example .env

# 4. Iniciar en desarrollo
npm run dev           # frontend
npm run dev:api       # backend
```

### Con Docker

```bash
docker-compose up --build
```

La app estará disponible en `http://localhost:3000`.

## 📁 Estructura del proyecto

```
nombre-proyecto/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   └── utils/
│   └── package.json
├── backend/
│   ├── src/
│   │   ├── routes/
│   │   ├── controllers/
│   │   ├── models/
│   │   └── middleware/
│   └── package.json
├── docker-compose.yml
├── .env.example
└── README.md
```

## 🔐 Variables de entorno

Copia `.env.example` a `.env` y rellena los valores:

```env
# App
NODE_ENV=development
PORT=3000

# Base de datos
DATABASE_URL=postgresql://user:password@localhost:5432/dbname

# Autenticación
JWT_SECRET=tu_secreto_super_seguro
JWT_EXPIRES_IN=7d

# API Keys externas
STRIPE_SECRET_KEY=
SENDGRID_API_KEY=
```

> ⚠️ Nunca subas el archivo `.env` al repositorio.

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Por favor lee [CONTRIBUTING.md](CONTRIBUTING.md) antes.

```bash
# 1. Haz un fork del proyecto
# 2. Crea tu rama de feature
git checkout -b feature/nueva-funcionalidad

# 3. Commitea tus cambios
git commit -m "feat: agrega nueva funcionalidad"

# 4. Push a la rama
git push origin feature/nueva-funcionalidad

# 5. Abre un Pull Request
```

## 📄 Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).

---

Hecho con ❤️ por [@tu-usuario](https://github.com/DiegoCac/DiegoCac.git)
