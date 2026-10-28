# Desarrollo de Aplicaciones Web

Repositorio de prácticas de la materia. La portada (`index.html`) enlaza a cada práctica y se publica con GitHub Pages.

## Estructura

```
.
├── index.html            # Portada con la lista de prácticas
├── css/portal.css        # Estilos de la portada
└── practicas/
    ├── 01-hoja-de-vida/  # Cada práctica es independiente
    │   ├── index.html
    │   ├── css/
    │   └── assets/
    └── 0X-nombre/
```

## Agregar una práctica

1. Crea una carpeta `practicas/0X-nombre/` con su propio `index.html`.
2. Usa rutas **relativas** (`css/style.css`, no `/css/style.css`) para que funcione en GitHub Pages.
3. Agrega una tarjeta en el `index.html` de la raíz.

## Prácticas con PHP

GitHub Pages solo sirve archivos estáticos (HTML, CSS, JS): **no ejecuta PHP**. Para esas prácticas:

- Guarda el código igual en `practicas/0X-nombre/`.
- Ejecútalas localmente: `php -S localhost:8000` dentro de la carpeta (o con XAMPP).
- En la portada, enlaza la tarjeta al código en GitHub en lugar de a la página.
- Si necesitas que se vean en línea, usa un hosting con PHP (InfinityFree, 000webhost, Render, etc.).

