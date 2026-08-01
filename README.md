# Jlsize — Catálogo web

Página web responsive creada con **HTML y CSS**, lista para publicar en GitHub Pages.

## Estructura

```text
jlsize_catalogo_git/
├── index.html
├── styles.css
├── README.md
└── assets/
    └── images/
        └── .gitkeep
```

## Cómo agregar las imágenes

1. Guarda tus fotos o mockups dentro de `assets/images/`.
2. Abre `index.html`.
3. Busca comentarios como este:

```html
<!-- <img src="assets/images/hoja-membretada.jpg" alt="Hoja membretada Jlsize"> -->
```

4. Elimina el bloque `<div class="image-placeholder...">...</div>` que está debajo.
5. Quita los signos de comentario `<!--` y `-->` de la etiqueta `<img>`.
6. Usa exactamente el mismo nombre de archivo o cambia la ruta.

Ejemplo final:

```html
<div class="product-media">
  <img src="assets/images/hoja-membretada.jpg" alt="Hoja membretada Jlsize">
</div>
```

## Imágenes previstas

- `hero-jlsize.jpg`
- `origen-ropa.jpg`
- `modelo-estilo.jpg`
- `hoja-membretada.jpg`
- `tarjeta-frontal.jpg`
- `tarjeta-posterior.jpg`
- `carnet-frontal.jpg`
- `carnet-posterior.jpg`
- `carpeta.jpg`
- `sobres.jpg`
- `patron-empaque.jpg`
- `elemento-extra.jpg`
- `brand-board.jpg`

No es obligatorio usar esos nombres, pero facilitan la edición.

## Datos que debes cambiar

En la sección `#contacto` del archivo `index.html`, reemplaza:

- `@tuusuario`
- `+507 0000-0000`
- `correo@ejemplo.com`
- Los enlaces `href="#"`

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub.
2. Sube todos los archivos manteniendo la misma estructura.
3. Ve a **Settings → Pages**.
4. En **Build and deployment**, selecciona `Deploy from a branch`.
5. Selecciona la rama `main` y la carpeta `/root`.
6. Guarda y espera a que GitHub muestre la dirección pública.

## Colores de marca

```css
--blue: #055594;
--red: #d42e2e;
--cream: #f6f4f0;
```

Puedes cambiarlos al inicio de `styles.css`.
