# Kaos Coffee — Oaxaca

Landing simple de **CGL Design** (versión 4: desktop + móvil).

> **Deploy directo del export de Google Stitch**
> (`stitch_kaos_coffee_shop_portal (3).zip`). Los datos salieron del export,
> no del dueño.

## Qué hay aquí

| Ruta | Origen en el zip |
|---|---|
| `/` | `kaos_coffee_shop_web_desktop/code.html` (landing desktop, secciones `#menu` `#galeria` `#comunidad` `#ubicacion`) |
| `/movil` | `kaos_coffee_shop_landing_m_vil/code.html` (landing móvil, secciones `#menu-seccion` `#comunidad-seccion` `#ubicacion-seccion`) |
| `DESIGN.md` | `electric_oaxaca_minimal/DESIGN.md` |
| `vercel.json` | Config mínima para estático en Vercel (`cleanUrls`) |

## Navegación

Snippet `CGL-NAV` antes de `</body>` en ambas páginas: cablea los botones
con `href="#"` a las anclas de la misma landing (`#top`, `#menu`,
`#comunidad`, `#ubicacion` y sus equivalentes `-seccion` en móvil).
Los links externos (Maps, WhatsApp, Instagram) quedan intactos.
Además se agregó `id="top"` al `body` y `id="comunidad-seccion"` a la
sección de comunidad en móvil (el export no los traía).

## Origen

- Zip: `stitch_kaos_coffee_shop_portal (3).zip` (36MB: 2 landings + fotos)
- Traza completa en `../_stitch-export/`

---

CGL Design · Páginas web para negocios de barrio en Oaxaca de Juárez
