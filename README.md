# NeoERP

**NeoERP** es un ERP moderno fullstack construido con **MERN** (MongoDB, Express, React, Node.js), **Zustand** para estado global, **Atomic Design** para componentes, **TanStack Query** para fetch/caching de datos y **TailwindCSS** para estilos.  
Está pensado para la gestión completa de clientes, productos, órdenes de trabajo/ventas y dashboard administrativo, con roles y control de permisos.

---

## 🛠 Tecnologías y herramientas

### Frontend
- React + Vite
- TailwindCSS
- Zustand (estado global)
- TanStack Query (fetching y caching)
- React Router (navegación)
- React Hook Form (formularios)

### Backend
- Node.js + Express
- MongoDB + Mongoose
- JWT (autenticación)
- Bcrypt (hash de contraseñas)
- Cors y dotenv

### Deploy
- Vercel (frontend)
- Railway o Vercel Functions (backend)

### Desarrollo
- ESLint, Prettier
- Git + GitHub
- Postman / Thunder Client

---

## ⚡ Características iniciales

- Autenticación con roles (Admin, Manager, User)
- CRUD de Clientes
- CRUD de Productos y Categorías
- Gestión de Órdenes de Trabajo / Ventas
- Dashboard con KPIs y últimas actividades
- Arquitectura basada en **Atomic Design**
- Fetching optimizado con **TanStack Query**
- Estado global ligero con **Zustand**
- Responsive con **TailwindCSS**

---

## 📂 Estructura del proyecto

### Backend (`neoerp-backend`)
<img width="402" height="259" alt="image" src="https://github.com/user-attachments/assets/227e1404-b9c5-4fbe-bace-2f92ce4ce5fb" />


### Frontend (`neoerp-frontend`)
<img width="439" height="482" alt="image" src="https://github.com/user-attachments/assets/a35817a3-7d9c-4f48-9895-31c27fc46b86" />


---

## 🚀 Instalación y uso

### Backend
```bash
cd neoerp-backend
npm install
cp .env.example .env
# Configurar variables: MONGO_URI, JWT_SECRET, PORT
npm run dev
```

---

### Frontend
```bas
cd neoerp-frontend
npm install
npm run dev
```

## 🧩 Scripts útiles

Backend

```bas
| Script        | Descripción                                        |
| ------------- | -------------------------------------------------- |
| `npm run dev` | Ejecuta el servidor en modo desarrollo con nodemon |
| `npm start`   | Ejecuta el servidor en producción                  |
| `npm test`    | Ejecuta pruebas unitarias (si se agregan)          |
```

Frontend
```bas
| Script            | Descripción                             |
| ----------------- | --------------------------------------- |
| `npm run dev`     | Ejecuta Vite en modo desarrollo         |
| `npm run build`   | Genera build optimizado para producción |
| `npm run preview` | Previsualiza el build de producción     |
```

🗂 Flujo de desarrollo sugerido

- Crear backend con Express + MongoDB, modelos y autenticación básica.
- Configurar frontend con Vite + Tailwind + React Router + Atomic Design.
- Integrar TanStack Query para fetching/caching de datos.
- Implementar Zustand para estado global (usuario, permisos, notificaciones).
- Crear páginas principales: Dashboard, Clientes, Productos, Órdenes.
- Añadir roles y protección de rutas.
- Mejorar UI/UX con Tailwind y componentes reusables.
- Preparar deploy en Vercel (frontend) y Railway/Vercel Functions (backend).

---

## 🧭 Arquitectura conceptual

```bas
Frontend (React) <---> Backend (Express + Node.js) <---> MongoDB
     |                         |                         |
     |---TanStack Query--------|                         |
     |---Zustand State----------                         |
     |---Atomic Components------------------------------>|
```
---

## 📈 Próximos pasos

- Completar CRUD de Clientes, Productos y Órdenes
- Implementar dashboards con KPIs y gráficos
- Crear notificaciones y alertas en tiempo real
- Añadir reportes exportables (PDF/Excel)
- Optimizar rendimiento y seguridad
- Desplegar en producción con Vercel / Railway

---

# 📜 Licencia

- NeoERP es open-source. Puedes usar, modificar y distribuir libremente el código bajo tu responsabilidad.

---

## 👨‍💻 Contacto

- Desarrollador: Pedro Osorio
- Email: pedro@example.com
- GitHub: github.com/pedroosorio
