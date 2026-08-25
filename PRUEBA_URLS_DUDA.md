# PRUEBA DE URLS DUDA — NO CANÓNICA

Esta copia existe solo para probar en un repositorio GitHub Pages separado si las rutas principales de la web Duda pueden conservarse de forma práctica.

## Rutas españolas preparadas

- Inicio: `/`
- Carta: `/carta/` (probar también `/carta`)
- Eventos: `/Eventos/` (probar también `/Eventos`)
- Reservas: `/reservas/` (probar también `/reservas`)
- Aviso legal: `/privacy/` (probar también `/privacy`)

La mayúscula de `Eventos` se conserva deliberadamente porque esa es la ruta pública observada en Duda.

## Capa SEO técnica añadida

- Canonical en las 15 páginas ES/EN/FR.
- Hreflang recíproco ES/EN/FR + x-default.
- `robots.txt` y `sitemap.xml`.
- JSON-LD `Restaurant` limpio en la portada.
- Se restaura en portada la descripción SEO observada en Duda, corrigiendo la errata «del leña» → «de leña».

## Qué NO se ha hecho todavía

- No se han implementado redirecciones históricas 301.
- No se han resuelto URLs históricas/ocultas como `/menu`, `/Regresamos`, etc.
- Sigue pendiente el PDF francés `assets/cartas/menu-fr.pdf`, actualmente enlazado pero ausente.
- No es todavía el ZIP canónico de producción.

Objetivo: subir esta copia a un repositorio de prueba, activar Pages y comprobar el comportamiento real de GitHub Pages antes de decidir la estructura final.
