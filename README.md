# OTARTE · Web (v1)

Este ZIP ya trae una web lista (landing comercial) para OTARTE.

## Lo que falta para dejarla 100% final
- **Logo real**: `assets/logo-otarte.png`
- **Imagen principal** (hero): `assets/hero.jpg`
- **Imagen para compartir en redes**: `assets/og.jpg` (recomendado 1200×630)
- **Favicon**: `assets/favicon.png`
- **Fotos de productos**: `assets/img/` (6 fotos; ahora son placeholders)
- **Direcciones reales (horario ya puesto: Lunes a domingo: 07:00–14:00 y 17:00–20:00)** (yo los relleno cuando me los pases)

## Cómo publicarla (GitHub Pages) — sin tocar código
1) En GitHub crea un repositorio (por ejemplo: `otarte-web`)
2) Sube **TODO el contenido del ZIP** al repositorio (arrastrar/soltar)
3) Settings → Pages → “Deploy from a branch” → Branch: `main` → Folder: `/(root)`
4) GitHub te dará una URL pública tipo:
   `https://TUUSUARIO.github.io/otarte-web/`

## Publicarla para Google
Cuando ya esté online:
- Alta en **Google Search Console (Consola de Búsqueda de Google)** y pedir indexación de la URL.
- Añadir la URL a la ficha de Google (Google Business Profile / Perfil de Empresa).

## Si quieres dominio propio
Puedes conectar un dominio más adelante. Se hace desde Settings → Pages (Custom domain).


## Nota de diseño
- Se cambió el diseño a un estilo **claro y cálido** (fondo crema) con acentos naranja OTARTE.

## Importante (para que se vea moderno en GitHub Pages)
- Asegúrate de subir **index.html**, **styles.css**, la carpeta **assets/** y el archivo **.nojekyll** en la raíz del repositorio.
- Si ves la web “sin diseño”, normalmente es porque **styles.css no está en la raíz** o GitHub Pages está apuntando a otra carpeta.
