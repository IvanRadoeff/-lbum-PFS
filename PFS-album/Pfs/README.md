# Álbum Garden Warfare

## Temática elegida
Este proyecto consiste en un álbum digital inspirado en el videojuego **Plants vs. Zombies: Garden Warfare**. El objetivo es representar un álbum de figuritas con diferentes personajes, variantes, habilidades y páginas especiales utilizando únicamente HTML y CSS.

## Descripción general
La aplicación comienza con una portada desde la que el usuario puede acceder al álbum. A medida que avanza mediante botones de navegación, puede recorrer distintas páginas donde se muestran:

- Personajes principales.
- Variantes de Lanzaguisante, Carnívora, Girasol y Cactus.
- Una página que anuncia las futuras variantes de los zombis.
- Una página de personajes especiales de la colaboración con Cheetos.
- Una página de Modo Jefes con Dave el Loco y Dr. Zomboss.
- Música de fondo que puede reproducirse durante la navegación.

La navegación entre páginas se realiza mediante enlaces internos (`#id`), por lo que no fue necesario utilizar JavaScript.

---

## Tecnologías utilizadas

- HTML5
- CSS3
- Visual Studio Code
- Google Chrome

---

## Cómo abrir y ejecutar el proyecto

1. Descargar o descomprimir la carpeta del proyecto.
2. Verificar que las carpetas **Imagenes** y **Musica** estén dentro del proyecto.
3. Abrir el archivo **index.html** con un navegador web (preferiblemente Google Chrome).
4. Utilizar los botones de navegación para recorrer el álbum.

---

## Organización de carpetas

```
Proyecto/
│
├── index.html
├── diseño.css
├── README.md
│
├── Imagenes/
│   ├── Portadareal.png
│   ├── FONDO.png
│   ├── FONDO2.png
│   ├── FONDO3.png
│   ├── personajes
│   ├── variantes
│   └── habilidades/
│   |   ├── DAVE.png
│   |   └── Zomboss.png
    └── Fondos/
│       ├── FONDO.png
│       ├── FONDO2.png
│       ├── FONDO3.png
└── Musica/
    └── MusicaFondo.mp3
```

---

## Características principales

- Navegación entre páginas mediante enlaces internos.
- Diseño realizado completamente con CSS.
- Uso de Grid y Flexbox para organizar las figuritas.
- Fondos personalizados para cada sección.
- Reproductor de música integrado.
- Todos los recursos se encuentran almacenados localmente dentro del proyecto.