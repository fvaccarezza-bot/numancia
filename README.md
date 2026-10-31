# Numancia Innovación · sitio web

Landing estática (HTML + CSS en un solo archivo). No necesita build.

## Estructura
```
index.html     página completa (estilos incluidos)
img/           imágenes exportadas de Figma (1x y @2x)
fonts/         PP Telegraf Ultrabold (.woff2) — requiere licencia web
```

## Imágenes que espera la página
Exportar desde Figma (frame "10 · Landing · desktop", ya tienen export 1x y @2x):

- hero-placa-petri.png
- tesis-foto.jpg
- objetivo-1.png, objetivo-2.png
- hitos.png
- condicion-ciencia.jpg, condicion-region.jpg, condicion-mercado.jpg

Cada una con su versión `@2x`. Si falta una, la página muestra un placeholder con el nombre del archivo.

## Tipografías
- Geist y Geist Mono: Google Fonts (ya enlazadas).
- PP Telegraf Ultrabold: poner `PPTelegraf-Ultrabold.woff2` en `fonts/`.
  Hace falta licencia **web** de Pangram Pangram. Mientras no esté, usa Archivo como reemplazo.
  ⚠️ Si se suben las fuentes, mantener el repo **privado**.

## Ver en local
Abrir `index.html` en el navegador, o:
```
npx serve .
```

## Publicar
Conectar el repo a Netlify o Vercel (sin build command, carpeta raíz `/`). Cada push actualiza el sitio.

## Pendiente con Frani
Logotipo final, personaje, nombre de las dos áreas, mail de contacto, disclaimer CNV, licencia de la fuente.
