# 🐾 Mokepon Multiplayer Game

Aplicación web interactiva tipo videojuego, desarrollada con JavaScript, donde el usuario selecciona una mascota, se mueve en un mapa y combate contra otros jugadores en tiempo real mediante un servidor backend.

---

## 🧠 Descripción

Mokepon es un juego web inspirado en mecánicas de combate por turnos.  
Incluye interacción en el navegador, renderizado en canvas y comunicación con un servidor usando HTTP.

El proyecto fue desarrollado como parte del proceso de aprendizaje en programación web, aplicando conceptos tanto de frontend como backend.

---

## 🛠️ Tecnologías utilizadas

- JavaScript (ES6+)
- HTML5
- CSS3
- Canvas API
- Node.js
- Express
- Fetch API
- JSON

---

## ⚙️ Funcionalidades

- Selección de personaje (Mokepon)
- Renderizado dinámico en canvas
- Movimiento en mapa en tiempo real
- Detección de colisiones
- Sistema de combate por turnos
- Comunicación cliente-servidor (API REST)
- Multijugador básico mediante sincronización de posiciones
- Envío y recepción de ataques entre jugadores

---

## 🧩 Arquitectura

### Frontend
- Manipulación del DOM
- Renderizado con Canvas
- Lógica del juego (movimiento, combate, eventos)
- Consumo de API con `fetch`

### Backend
- Servidor con Express
- Manejo de rutas REST:
  - `/unirse`
  - `/mokepon/:jugadorId`
  - `/posicion`
  - `/ataques`
- Gestión de jugadores en memoria
- Sincronización de estado entre clientes

---

## 📁 Estructura del proyecto
mokepon
│
├ public
│ ├ assets
│ ├ index.html
│ ├ mokepon.js
│ └ style.css
│
├ index.js
├ package.json
└ package-lock.json

---

## ▶️ Instalación y ejecución

1. Clonar repositorio

```bash
git clone https://github.com/mateonyx1304/mokepon-terminado

2. Instalar dependencias (terminal)

npm install

3. Ejecutar servidor (terminal)

node index.js

4. Abrir en navegador

http://localhost:8080

## 📚 Conceptos aplicados

- Programación orientada a objetos (POO)  
- Manejo de eventos  
- Asincronía (promesas y fetch)  
- Arquitectura cliente-servidor  
- APIs REST  
- Debugging y resolución de errores reales (404, 500, rutas, MIME)  

---

## 🎯 Aprendizajes clave

- Construcción de un sistema completo frontend + backend  
- Comunicación entre múltiples clientes mediante servidor  
- Manejo de estados en aplicaciones interactivas  
- Resolución de errores en entorno real de desarrollo  

---

## 🔮 Posibles mejoras

- Implementación de WebSockets para comunicación en tiempo real  
- Persistencia de datos con base de datos  
- Sistema de autenticación de usuarios  
- Mejora de interfaz y experiencia de usuario (UI/UX)  
- Despliegue en la nube  

---

## 👨‍💻 Autor

**Mateo Ángel**  
Desarrollador en formación enfocado en JavaScript, backend y construcción de productos digitales.
