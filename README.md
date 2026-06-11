# 🌙 El Camino al Uno · Espacio de consciencia

PWA de crecimiento interior y consciencia desarrollada para **Tatiana**, acompañante de consciencia en formación como coach. Primera versión enfocada en **diario personal** y **prácticas guiadas**, con enfoque espiritual/gnóstico puro.

> Desarrollada por **Vibras Positivas HM** — Derechos de Autor Reservados
> Caucasia, Antioquia · Colombia

---

## ✨ Funcionalidades (v1)

| Sección | Descripción |
|---|---|
| 🏠 **Inicio** | Reflexión del día (21 enseñanzas que rotan automáticamente según la fecha de Colombia, UTC-5) con el círculo dorado animado, símbolo del Uno. |
| 📖 **Diario de consciencia** | Escritura libre con guardado local. Las entradas quedan fechadas con día y hora de Colombia. Eliminación con confirmación. |
| 🧘 **Prácticas guiadas** | Respiración consciente 4·4·6 con círculo animado que guía inhalación, retención y exhalación. Meditación en silencio con temporizador (5/10/15/20 min) y campana suave (432 Hz) al finalizar. |
| 💬 **Tatiana** | Perfil de la coach y botón directo de WhatsApp para agendar sesión (mensaje pre-formateado). |

## 🔒 Privacidad — Habeas Data (Ley 1581 de 2012)

- Las entradas del diario se guardan **únicamente en el dispositivo del usuario** (`localStorage`). No se envían a ningún servidor ni a terceros.
- Aviso de privacidad visible en la sección del diario.
- Aviso de tratamiento de datos de contacto junto al botón de WhatsApp.

## 📱 PWA

- `manifest.json` con íconos 192 y 512, `display: standalone`, tema `#160F2E`.
- `sw.js` (Service Worker) con caché para funcionamiento **offline**.
- Open Graph y Twitter Cards para vista previa al compartir por WhatsApp/redes.
- Instalable en Android, iOS y escritorio ("Agregar a pantalla de inicio").

## 🎨 Diseño

- Paleta mística-elegante: violeta noche `#160F2E`, dorado `#D4AF6A`, crema `#F4E9CD`, lavanda `#9D8FC7`.
- Tipografías: **Cormorant Garamond** (display) + **Karla** (cuerpo).
- Firma visual: el **círculo dorado con punto central** — representación del Uno y guía de la respiración.
- Mobile-first, navegación inferior fija, respeta `prefers-reduced-motion`.

## 📂 Archivos

```
index.html      → Aplicación completa (HTML + CSS + JS, un solo archivo)
manifest.json   → Manifiesto PWA
sw.js           → Service Worker (offline)
icon-192.png    → Ícono PWA 192×192
icon-512.png    → Ícono PWA 512×512
README.md       → Este archivo
```

## 🚀 Despliegue

Compatible con **GitHub Pages**, **Netlify** o **Hostinger**. Subir los 5 archivos a la raíz (o carpeta del proyecto) y listo.

**Después de desplegar, actualizar en `index.html`:**
1. `og:url` → URL final de la app.
2. `og:image` → URL absoluta de `icon-512.png` (WhatsApp requiere URL absoluta para la vista previa).

## ⚙️ Personalización rápida

| Qué | Dónde |
|---|---|
| WhatsApp de Tatiana | Constante `WHATSAPP` en `index.html` (actual: `573132872150`) |
| Foto de Tatiana | Reemplazar el `<div class="avatar">T</div>` por `<img>` cuando haya foto |
| Bio de la coach | Párrafo `.perfil-bio` |
| Reflexiones diarias | Arreglo `REFLEXIONES` (21 entradas, ampliable) |
| Nombre de la app | `<title>`, `manifest.json` y encabezado `h1.brand` |

## 🗺️ Roadmap sugerido (v2)

- Ruta de aprendizaje por módulos con progreso.
- Más prácticas (gratitud guiada, escaneo corporal).
- Galería/testimonios de Tatiana cuando tenga material gráfico.
- Frecuencias/sonidos ambientales para meditar.

---

**Desarrollada por Vibras Positivas HM — Derechos de Autor Reservados**
