# 🔮 Tarot Cards App

Una aplicación web interactiva que simula una lectura de cartas de tarot. Puedes hacer una pregunta y obtener una carta al azar, o ver todas las cartas disponibles con sus significados.

## Descripción

La aplicación obtiene cartas desde la API pública [Tarot API](https://tarotapi.dev) y muestra su significado y descripción. Además, combina esas cartas con imágenes personalizadas guardadas localmente. Para esto, utiliza un array en un archivo .js donde se define cada carta junto con la ruta de su imagen correspondiente desde la carpeta tarotdeck.

## Tecnologías utilizadas

- HTML5
- CSS3 (Responsive y estilizado con fuentes místicas)
- JavaScript (Vanilla)
- [Tarot API](https://tarotapi.dev) para la información de las cartas

## Funcionalidades

- Mostrar una carta de tarot aleatoria al hacer una pregunta.
- Ver todas las cartas disponibles.
- Mostrar imágenes personalizadas para cada carta (ubicadas en `/tarotdeck`).
- Interfaz responsiva para dispositivos móviles.


## Cómo usar

1. Clona el repositorio.
2. Abre `index.html` en tu navegador.
3. Escribe una pregunta y presiona "Ask" o haz clic en "Show all cards".