# El Bajoncito Delivery

este es el sitio web **El Bajoncito**, un emprendimiento de delivery de postres y gomitas. Es parte de mi proyecto para el trabajo practico Nº1

El sitio está hecho solo con HTML y CSS, es una página de una sola pantalla (One-Page) con navegación por secciones.

## Secciones

| Sección | Descripción |
| --- | --- |
| **Header** | Logo y menú de navegación con links a cada sección, más un botón de pedido. |
| **Hero** | Portada con el único `<h1>`, logo de la marca y botones de llamado a la acción. |
| **Barra rápida** | Resumen de beneficios del servicio. |
| **Menú (Cards)** | 3 tarjetas con imagen, título `<h3>`, descripción y botón de acción, alineadas con Flexbox. |
| **Precios** | Lista de productos y combos con sus valores. |
| **Galería** | Mosaico de imágenes con Flexbox y `flex-wrap`, que se acomoda según el ancho de pantalla. |
| **Contacto** | Formulario con labels asociados, selector, opciones y botones de enviar y limpiar. También links a Instagram y WhatsApp. |
| **Footer** | Logo y links de navegación. |

## Formulario de contacto

Campos del formulario:

- Nombre (`text`)
- Email (`email`)
- Teléfono (`tel`, solo números)
- Motivo de contacto (`select` con varias opciones)
- Modalidad (`radio`: Delivery o Take away)
- Comentarios (`textarea`)
- Novedades (`checkbox`)

Botones: **Enviar** (`submit`) y **Limpiar formulario** (`reset`). El envío usa `mailto:`, por lo que abre el cliente de correo del usuario.

## Tecnologías

- **HTML5 semántico:** `header`, `nav`, `main`, `section`, `figure`, `form` y `footer`.
- **CSS3:** variables (`:root`), Flexbox para todo el layout, transiciones y `prefers-reduced-motion`.
- **Google Fonts:** *Space Grotesk* para títulos y *DM Sans* para el texto.

## Diseño responsive

Se adapta con Media Queries a tres tamaños:

Celular | hasta 760px |
Tablet | hasta 1050px |
Escritorio | más de 1050px |


## Autor

**[Matias Ezequiel Peccia]**
Curso Inicial Front-End, UTN.