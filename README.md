# EcoHaven Group LLC · Sitio web

Sitio estático (HTML + JavaScript), listo para publicar en Netlify sin paso de compilación.

- `index.html`: página principal (diseño estilo Launchfolio, bilingüe EN/ES, HTML y CSS sin dependencias). Presenta a EcoHaven como minorista omnicanal (tiendas en Panamá, tienda en línea propia y Amazon).
- `assets/`: logos.
- El formulario de contacto para proveedores usa Netlify Forms (formulario `mayoreo`). Las solicitudes llegan al panel de Netlify, en Forms, y se pueden reenviar por correo a sales@ecohaven.co.

## Publicar
1. En Netlify: Add new site → Import an existing project → GitHub → `ecohaven-web`. Sin comando de build; carpeta de publicación `.`.
2. Domain management → Add domain → `ecohaven.co`, y copiar en el proveedor del dominio los registros DNS que indique Netlify.
3. Forms → activar la detección de formularios y agregar una notificación por correo a sales@ecohaven.co.
