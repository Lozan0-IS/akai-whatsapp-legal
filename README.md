# AKAI · páginas legales

Sitio estático (HTML y CSS, sin dependencias ni scripts) con las páginas legales de AKAI para usar en Meta for Developers.

| Página | Archivo |
|---|---|
| Inicio | `index.html` |
| Política de privacidad | `privacy-policy.html` |
| Eliminación de datos | `data-deletion.html` |
| Condiciones del servicio | `terms.html` |

Publicado con GitHub Pages desde la rama `main`, carpeta raíz:
`https://lozan0-is.github.io/akai-whatsapp-legal/`

## Estado: borrador

Los textos describen el diseño actual de AKAI, que está en desarrollo. **No son asesoría legal** y deben revisarse antes del lanzamiento comercial y antes de enviar la app a revisión de Meta.

## Marcadores pendientes

**Contacto confirmado:** `helloakaistudio@gmail.com` (privacidad, condiciones y solicitudes de eliminación). Que el correo exista no significa que el proceso de eliminación esté validado: eso sigue marcado como pendiente en la página.

Cada dato no confirmado está visible en la página como `[… PENDIENTE]`. Antes de la revisión de Meta hay que sustituirlos:

| Marcador | Dónde |
|---|---|
| `[ENTIDAD LEGAL PENDIENTE]` | privacidad, condiciones |
| `[VALIDACIÓN DEL PROCESO DE ELIMINACIÓN PENDIENTE]` | eliminación de datos |
| `[PLAZO DE CONSERVACIÓN PENDIENTE]` | privacidad, eliminación de datos |
| `[PLAZO DE RESPUESTA A SOLICITUDES PENDIENTE]` | privacidad, eliminación de datos |
| `[PROVEEDORES DE INFRAESTRUCTURA PENDIENTES]` / `[…Y DE IA PENDIENTES]` | privacidad |
| `[FECHA DE VIGENCIA PENDIENTE]` | condiciones |
| `[CONDICIONES COMERCIALES Y PRECIOS PENDIENTES]` | condiciones |
| `[LIMITACIÓN DE RESPONSABILIDAD PENDIENTE]` | condiciones |
| `[JURISDICCIÓN Y LEY APLICABLE PENDIENTE]` | condiciones |

Para localizarlos: `grep -n "PENDIENTE" *.html`. Al resolverlos, actualiza también la fecha de «última actualización» de cada página.

## Reglas de este repositorio

- Solo contiene este sitio. No hay credenciales, tokens ni datos personales; no deben añadirse.
- No se carga nada de terceros (ni fuentes, ni scripts, ni analítica).
- Los enlaces externos son solo a las políticas oficiales de Meta y WhatsApp.

## Vista previa local

Abre `index.html` en un navegador, o desde esta carpeta: `python -m http.server 8000` y visita `http://localhost:8000`.
