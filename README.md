# Numancia Innovación · sitio web

Landing estática (HTML + CSS en un solo archivo). No necesita build.

## Estructura
```
index.html     página completa (estilos incluidos)
img/           imágenes exportadas de Figma (1x y @2x)
fonts/         PP Telegraf Ultrabold (.woff2) — requiere licencia web
```

## Estado
Desktop a **1440 px fijo**, armado desde el frame "Landing · desktop" de Figma (nodo 219:425). Mobile: pendiente.

## Imágenes (`img/`)
Exportadas del Figma a 1x (fondo transparente donde corresponde). Para nitidez en pantallas retina,
reexportar a 2x desde Figma: los layers ya tienen export 1x y @2x configurado.

hero-molecula · tesis-foto · tesis-planilla · objetivo-1/2 · hitos · foto-ciencia/region/mercado · cinta ·
cita-foto · areas-vivir/producir · forma-amarilla/violeta · mas-1/2/3 · mapa

## Tipografías
- Geist y Geist Mono: Google Fonts (ya enlazadas).
- PP Telegraf: poner `PPTelegraf-Ultrabold.woff2` y `PPTelegraf-Regular.woff2` en `fonts/`.
  Hace falta licencia **web** de Pangram Pangram. Mientras no esté, usa Archivo como reemplazo.
  ⚠️ El repo es público: NO subir los archivos de la fuente. Cargarlos directo en el hosting (Netlify/Vercel) o en el servidor.

## Ver en local
Abrir `index.html` en el navegador, o:
```
npx serve .
```

## Publicar
Conectar el repo a Netlify o Vercel (sin build command, carpeta raíz `/`). Cada push actualiza el sitio.

## Pendiente con Frani
Logotipo final, personaje, nombre de las dos áreas, mail de contacto, disclaimer CNV, licencia de la fuente.
