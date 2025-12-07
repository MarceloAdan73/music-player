# 🎵 Music Player - Angular

[![Angular](https://img.shields.io/badge/Angular-21.0.0-DD0031?style=for-the-badge&logo=angular&logoColor=white)](https://angular.io/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9.3-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

**🌐 Live Demo:** [https://music-player-roan-eight.vercel.app/](https://music-player-roan-eight.vercel.app/)

Un reproductor de música moderno, completamente responsive y funcional construido con Angular 21.

## ✨ Características principales

- 🎨 **Diseño moderno** con gradientes CSS3 y animaciones fluidas
- 🎵 **Reproducción de audio** con HTML5 Audio API
- 📱 **Completamente responsive** (mobile, tablet, desktop)
- 🎯 **Indicador visual** de canción en reproducción
- ⚡ **Optimización de rendimiento** con pre-carga de imágenes
- 🎨 **Tema oscuro moderno** con variables CSS
- 🔄 **Modo aleatorio** (shuffle) y navegación entre canciones
- ⏱️ **Barra de progreso** interactiva con seek
- 🔊 **Control de volumen** integrado
- 🖼️ **Portadas de álbumes** en formato WEBP optimizado

## 🚀 Comenzar

### Prerrequisitos
- Node.js 18 o superior
- npm 9 o superior
- Angular CLI 21

### Instalación local
```bash
# Clonar repositorio
git clone https://github.com/MarceloAdan73/music-player.git
cd music-player

# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
ng serve
```

## 📁 Estructura del Proyecto
```
Angular-Music-Player/
├── src/
│ ├── app/
│ │ ├── components/
│ │ │ └── song-list/
│ │ ├── services/
│ │ │ ├── audio.service.ts
│ │ │ ├── music-library.service.ts
│ │ │ └── image.service.ts
│ │ ├── models/
│ │ │ └── cancion.model.ts
│ │ ├── app.ts
│ │ ├── app.html
│ │ └── app.css
│ ├── assets/
│ │ ├── audio/
│ │ └── images/
│ └── index.html
├── angular.json
├── package.json
├── vercel.json
└── README.md
```
##🔧 Tecnologías Utilizadas
Angular 21 - Framework principal

TypeScript 5.9 - Tipado estático

HTML5 Audio API - Reproducción de audio nativa

CSS3 - Animaciones, gradientes y variables CSS

RxJS - Programación reactiva

Font Awesome - Iconografía

Angular Material - Componentes UI

Howler.js - Biblioteca de audio avanzada (disponible)

## 🎛️ Controles del Reproductor

###Controles principales
▶️ Play/Pause - Reproducir o pausar canción actual

⏮️ Anterior - Canción anterior en la lista

⏭️ Siguiente - Canción siguiente en la lista

🔀 Aleatorio - Activar/desactivar modo shuffle

🔊 Volumen - Control deslizante de volumen (70% por defecto)

## Visualización
🎨 Portadas de álbumes - Imágenes optimizadas en WEBP

📊 Barra de progreso - Interactiva con click para seek

⏱️ Tiempos - Duración y progreso formateados (mm:ss)

🔊 Estado de reproducción - Indicadores visuales

## 🌐 Despliegue en Vercel
La aplicación está desplegada automáticamente en Vercel con cada push a GitHub.

URL de producción: https://music-player-roan-eight.vercel.app/

### Configuración de Vercel
Framework: Angular (detección automática)

Build Command: npm run build

Output Directory: dist/music-player/browser

Configuración SPA: Rewrites para manejar rutas

Caché: Headers optimizados para archivos multimedia

### Construir para producción
``bash
# Construir aplicación
ng build --configuration production

# Los archivos estarán en dist/music-player/browser/
🚀 Comandos útiles
``bash

# Desarrollo
ng serve                    # Iniciar servidor de desarrollo (localhost:4200)
ng serve --port 4201       # Especificar puerto diferente
ng serve --open            # Abrir automáticamente en el navegador

# Build
ng build                   # Build para desarrollo
ng build --configuration production  # Build para producción
ng build --watch           # Build con watch mode para desarrollo

# Generación
ng generate component <nombre>  # Generar nuevo componente
ng generate service <nombre>    # Generar nuevo servicio
ng generate module <nombre>     # Generar nuevo módulo

# Testing
ng test                    # Ejecutar pruebas unitarias
🐛 Solución de Problemas Comunes
La primera canción no reproduce correctamente
bash
# Verificar consola del navegador para mensajes de error
# Asegurar que los archivos MP3 estén en la carpeta correcta
Archivos MP3 no se cargan en producción
typescript
// Verificar rutas en music-library.service.ts
// Deben ser relativas: 'assets/audio/nombre.mp3'
// NO absolutas: '/assets/audio/nombre.mp3'
Problemas de CORS o CSP
html
<!-- En index.html, asegurar política permisiva si es necesario -->
<meta http-equiv="Content-Security-Policy" content="default-src 'self'; media-src 'self' data:;">
La aplicación no se actualiza en Vercel
bash
# Forzar recarga limpiando caché
git add .
git commit -m "Update"
git push
# Vercel desplegará automáticamente
📄 Licencia
Este proyecto está licenciado bajo la Licencia MIT - ver el archivo LICENSE para más detalles.

🤝 Contribuir
Fork el proyecto

Crear rama de feature (git checkout -b feature/NuevaFuncionalidad)

Commit cambios (git commit -m 'Agregar NuevaFuncionalidad')

Push a la rama (git push origin feature/NuevaFuncionalidad)

Abrir Pull Request

✨ Créditos
Desarrollado por: Marcelo Adán

Diseño inspirado en: Spotify, Apple Music

Iconos: Font Awesome 6

Tipografía: Google Fonts

Despliegue: Vercel Platform

Hosting de código: GitHub

🔗 Enlaces importantes:

🌐 Live Demo: https://music-player-roan-eight.vercel.app/

📂 Repositorio: https://github.com/MarceloAdan73/music-player

🐛 Reportar issues: GitHub Issues

📧 Contacto: A través de GitHub

⭐ Si te gusta este proyecto, ¡dale una estrella en GitHub!


