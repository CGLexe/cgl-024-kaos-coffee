# Kaos Coffee — Oaxaca

Portal multipágina de **CGL Design**.

> **Esto es un deploy directo del export de Google Stitch.** Todavía no pasa
> por limpieza ni auditoría. Los datos salieron del export, no del dueño.

## Qué hay aquí

| Ruta | Origen en el zip |
|---|---|
| `/` | `kaos_coffee_shop_web_desktop/code.html` (72KB, página principal desktop) |
| `/menu` | `kaos_coffee_shop_men_galer_a_desktop/code.html` |
| `/menu-completo` | `kaos_men_completo_m_vil/code.html` |
| `/galeria` | `kaos_galer_a_interactiva_m_vil_compacta/code.html` |
| `/comunidad` | `kaos_comunidad_blaise_juegos/code.html` |
| `/ubicacion` | `kaos_ubicaci_n_horarios_m_vil/code.html` |
| `/inicio-movil` | `kaos_inicio_m_vil_optimizado_corto/code.html` |
| `DESIGN.md` | `electric_oaxaca_minimal/DESIGN.md` |
| `vercel.json` | Config mínima para estático en Vercel (`cleanUrls`) |
| `CGL-NAV` | Snippet inyectado antes de `</body>` en las 7 páginas: cablea los
botones del export (`data-path` o etiqueta con `href="#"`) a las rutas
reales (`/` · `/menu` · `/galeria` · `/comunidad` · `/ubicacion`).
Solo toca `href="#"`: Maps, WhatsApp e Instagram quedan intactos. |

## Origen

- Zip: `stitch_kaos_coffee_shop_portal.zip` en Descargas (36MB: 7 páginas + fotos)
- Fotos reales del local también en `Descargas/Kaos Coffe/`
- Traza completa en `../_stitch-export/`

---

CGL Design · Páginas web para negocios de barrio en Oaxaca de Juárez
