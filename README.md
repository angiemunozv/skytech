# SKYTECH — Sitio web

Página web estática de SKYTECH, creada con HTML, CSS y JavaScript.

## Archivos

- `index.html`: página principal.
- `assets/skytech-banner.png`: imagen principal del sitio.

## Configurar WhatsApp

Abre `index.html` y busca la línea:

```js
const SKYTECH_WHATSAPP = "";
```

Coloca el número de WhatsApp con código de país, solo números y sin `+`, espacios ni guiones. Para Perú, el formato comienza con `51`.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html`, la carpeta `assets` y este `README.md` a la raíz del repositorio.
3. En el repositorio, entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
6. Espera a que GitHub Pages publique el sitio. La dirección aparecerá en la misma sección **Pages**.

No cambies el nombre `index.html` ni la ubicación de la carpeta `assets`, porque la página utiliza esa ruta para mostrar el banner.
