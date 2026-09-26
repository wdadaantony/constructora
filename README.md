# Romerito Construcción

Sitio web en español para una empresa de casas prefabricadas. Incluye 12 páginas, galería con filtros, configurador de casa, solicitudes de cotización por WhatsApp, diseño adaptable, animaciones y pantalla de carga.

## Ver el sitio localmente

Requiere Node.js 20 o posterior. No requiere instalar dependencias.

```sh
npm start
```

Abre http://127.0.0.1:4173/.

## Editar y generar las páginas

- `site.mjs`: contenido y plantillas de las páginas.
- `dist/style.css`: diseño y estilos adaptables.
- `dist/app.js`: navegación, configurador, formularios y galería.
- `dist/assets/`: logotipo y fotografías utilizadas.
- `server.mjs`: servidor de vista previa local.

Después de editar `site.mjs`, ejecuta:

```sh
npm run build
```

Las páginas listas para un alojamiento estático se encuentran en `dist/` y se incluyen en este repositorio. La página de entrada es `dist/index.html`.

## Contacto y cotizaciones

Los formularios preparan una consulta que el visitante revisa y envía mediante WhatsApp. No hay un servidor de correo ni una base de datos de clientes. El configurador permite descargar un resumen de preferencias; no calcula precios. Los importes, plazos y cobertura deben confirmarse con la empresa.

El número `94566743` se muestra tal como fue proporcionado y está pendiente de confirmar.

## Imágenes

El logotipo y las imágenes locales fueron proporcionados para este proyecto. La galería diferencia los diseños de referencia del material de construcción. No se incluyen originales ajenos a las páginas ni archivos temporales de trabajo.

Imágenes referenciales externas:

- [Lieana Slapinsh / Unsplash](https://unsplash.com/photos/modern-triangular-cabins-with-large-windows-under-blue-sky-g69dIem5Emk)
- [Clay Banks / Unsplash](https://unsplash.com/photos/a-small-black-cabin-in-the-middle-of-a-field-pPhjlD9U4mA)

Las fuentes se cargan desde Google Fonts. El uso de estos recursos externos se explica en la página de privacidad.
