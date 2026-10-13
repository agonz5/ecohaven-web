# EcoHaven Group LLC · Sitio web

Sitio estático (HTML + JavaScript), listo para publicar en Netlify sin paso de compilación.

- `index.html`: página principal (diseño "Group A", bilingüe EN/ES).
- `opcion-b.html` y `opcion-original.html`: los otros dos diseños, para comparar. No aparecen en Google.
- `assets/`: logos.
- El formulario de cuentas mayoristas usa Netlify Forms (formulario `mayoreo`). Las solicitudes llegan al panel de Netlify, en Forms, y se pueden reenviar por correo a sales@ecohaven.co.

## Publicar
1. En Netlify: Add new site → Import an existing project → GitHub → `ecohaven-web`. Sin comando de build; carpeta de publicación `.`.
2. Domain management → Add domain → `ecohaven.co`, y copiar en el proveedor del dominio los registros DNS que indique Netlify.
3. Forms → activar la detección de formularios y agregar una notificación por correo a sales@ecohaven.co.
