# Dragon Ball Secrets

## Descripción

Web temática de Dragon Ball donde se muestran personajes usando datos obtenidos de una API.

## API utilizada

API utilizada: Dragon Ball API  
https://dragonball-api.com/

Los datos obtenidos son: nombre, raza, género, Ki, Ki máximo, descripción, imagen y afiliación.

## Campos utilizados

| Campo | Tipo |
|---|---|
| name | Texto |
| ki | Texto |
| maxKi | Texto |
| race | Texto |
| gender | Texto |
| description | Texto largo |
| image | URL |
| affiliation | Texto |

## Páginas

- **index.html:** Página principal con información de la temática y contenido multimedia.
- **catalogo.html:** Lista de personajes.
- **fichas/:** Fichas con información completa de los personajes.
- **comparativa.html:** Comparación entre personajes.
- **sobre-los-datos.html:** Explicación de la API y ejemplo de JSON.
- **propuesta.html:** Formulario para añadir nuevos personajes.

## Decisiones de marcado

- Se han usado etiquetas semánticas como `<header>`, `<nav>`, `<main>` y `<footer>` para organizar la página.
- En las fichas se han usado campos separados para mostrar correctamente los datos de la API.
- El formulario usa diferentes controles según el tipo de información.

## Multimedia

Se incluye un sonido de carga de Ki de Dragon Ball dentro de `assets/media`.

## Validación

Las páginas han sido revisadas con el validador HTML del W3C y se han corregido los errores encontrados.