🎵 Modern Music Player - Angular
https://img.shields.io/badge/Angular-21.0.0-DD0031?style=for-the-badge&logo=angular&logoColor=white
https://img.shields.io/badge/TypeScript-5.9.3-3178C6?style=for-the-badge&logo=typescript&logoColor=white
https://img.shields.io/badge/Deployed%2520on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white
https://img.shields.io/badge/License-MIT-blue?style=for-the-badge

🌐 Live Demo: https://music-player-roan-eight.vercel.app/

Un reproductor de música moderno, completamente responsive y funcional construido con Angular 21.

✨ Características principales
🎨 Diseño moderno con gradientes CSS3 y animaciones fluidas

🎵 Reproducción de audio con HTML5 Audio API y Howler.js

📱 Completamente responsive (mobile, tablet, desktop)

🎯 Indicador visual de canción en reproducción

⚡ Optimización de rendimiento con pre-carga de imágenes

🎨 Tema oscuro moderno con variables CSS

🔄 Modo aleatorio (shuffle) y navegación entre canciones

⏱️ Barra de progreso interactiva con seek

🔊 Control de volumen integrado

🖼️ Portadas de álbumes en formato WEBP optimizado

🎵 Canciones incluidas
"Al Compás de la Mentira" - Tren Loco (Heavy Metal)

"Caught Somewhere in Time" - Iron Maiden (Heavy Metal)

"Cuantas Palabras" - O'Connor (Rock)

"Down" - Stone Temple Pilots (Grunge Rock)

"Judas Oficio" - Malón (Heavy Metal)

"Let It Roll" - Velvet Revolver (Hard Rock)

🚀 Comenzar
Prerrequisitos
Node.js 18 o superior

npm 9 o superior

Angular CLI 21

Instalación local
bash
# Clonar repositorio
git clone https://github.com/MarceloAdan73/music-player.git
cd music-player

# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
ng serve
Construir para producción
bash
# Construir aplicación
ng build --configuration production

# Los archivos estarán en dist/music-player/browser/
🌐 Despliegue en Vercel
La aplicación está desplegada automáticamente en Vercel con cada push a GitHub.

URL de producción: https://music-player-roan-eight.vercel.app/

Configuración de Vercel
Framework: Angular (detección automática)

Build Command: npm run build

Output Directory: dist/music-player/browser

Variables de entorno: No requeridas

📁 Estructura del Proyecto
text
Angular-Music-Player/
├── src/
│   ├── app/
│   │   ├── components/
│   │   │   └── song-list/          # Componente de lista de canciones
│   │   ├── services/
│   │   │   ├── audio.service.ts    # Servicio de reproducción de audio
│   │   │   ├── music-library.service.ts  # Gestión de biblioteca musical
│   │   │   └── image.service.ts    # Servicio de imágenes
│   │   ├── models/
│   │   │   └── cancion.model.ts    # Interface de canción
│   │   ├── app.ts                  # Componente principal
│   │   ├── app.html                # Template principal
│   │   └── app.css                 # Estilos principales
│   ├── assets/
│   │   ├── audio/                  # Archivos MP3 (6 canciones)
│   │   └── images/                 # Portadas de álbumes en WEBP
│   └── index.html                  # HTML principal
├── angular.json                    # Configuración Angular
├── package.json                    # Dependencias y scripts
├── vercel.json                     # Configuración Vercel para SPA
└── README.md                       # Este archivo
🔧 Tecnologías Utilizadas
Angular 21 - Framework principal

TypeScript 5.9 - Tipado estático

HTML5 Audio API - Reproducción de audio

CSS3 - Animaciones y diseño responsive

RxJS - Programación reactiva

Font Awesome - Iconos

Angular Material - Componentes UI

Howler.js - Librería de audio avanzada (disponible)

Wavesurfer.js - Visualizador de ondas (disponible)

🎛️ Funcionalidades del Reproductor
Controles principales
▶️ Play/Pause - Reproducir o pausar canción actual

⏮️ Anterior - Canción anterior en la lista

⏭️ Siguiente - Siguiente canción en la lista

🔀 Aleatorio - Activar/desactivar modo aleatorio

🔊 Volumen - Control deslizante de volumen

Visualización
🎨 Portadas de álbumes - Imágenes optimizadas en WEBP

📊 Barra de progreso - Con seek interactivo

⏱️ Tiempos - Duración y tiempo actual formateado

🔊 Indicador de estado - Visualización de canción actual

Biblioteca musical
📋 Lista de canciones - Con scroll y selección

🏷️ Información detallada - Título, artista, álbum, género, año

🎵 Organización - Por orden de lista

🚀 Comandos útiles
bash
# Desarrollo
ng serve                    # Iniciar servidor de desarrollo
ng serve --port 4201       # Especificar puerto diferente

# Build
ng build                   # Build desarrollo
ng build --configuration production  # Build producción

# Testing
ng test                    # Ejecutar pruebas unitarias

# Generación
ng generate component <nombre>  # Generar nuevo componente
ng generate service <nombre>    # Generar nuevo servicio
📄 Licencia
Este proyecto está licenciado bajo la Licencia MIT - ver el archivo LICENSE para más detalles.

🤝 Contribuir
Fork el proyecto

Crear rama de feature (git checkout -b feature/AmazingFeature)

Commit cambios (git commit -m 'Add some AmazingFeature')

Push a la rama (git push origin feature/AmazingFeature)

Abrir Pull Request

✨ Créditos
Desarrollado por: Marcelo Adán

Diseño inspirado en: Reproductores modernos como Spotify y Apple Music

Iconos: Font Awesome

Tipografía: Google Fonts (Orbitron, Exo 2)

Despliegue: Vercel

Hosting de código: GitHub

🔗 Enlaces importantes:

🌐 Live Demo: https://music-player-roan-eight.vercel.app/

📂 Repositorio: https://github.com/MarceloAdan73/music-player

🐛 Reportar issues: GitHub Issues

⭐ Si te gusta este proyecto, ¡dale una estrella en GitHub!

