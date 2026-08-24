# Pixel Store

Sitio web de la tienda, listo para publicar en GitHub Pages.

## Cómo publicarlo (desde el celular)

1. Entra a **github.com** y crea una cuenta si no tienes una.
2. Toca el **+** arriba a la derecha → **"New repository"**.
   - Nombre: `pixel-store` (o el que prefieras)
   - Marca la casilla **"Public"**
   - Dale a **"Create repository"**
3. Dentro del repositorio recién creado, toca **"Add file" → "Upload files"**.
4. Sube estos archivos y carpetas tal cual están aquí:
   - `index.html`
   - la carpeta `assets` completa (con logo.png, banner.png, fondo.png, guia-usdt.png, guia-wallet.png)
5. Baja y dale a **"Commit changes"**.
6. Ve a **"Settings" → "Pages"** (menú lateral del repositorio).
7. En **"Branch"**, elige `main` y carpeta `/root`, luego **"Save"**.
8. Espera un minuto y arriba te va a aparecer el link de tu web, algo como:
   `https://tu-usuario.github.io/pixel-store/`

Ese link ya es tu tienda funcionando de verdad, accesible desde cualquier lugar sin bloqueos.

## Nota sobre las imágenes de productos y guías

Las imágenes de `logo.png`, `banner.png` y `fondo.png` ya están integradas directamente en el diseño.

Las imágenes de cada **producto** y de cada **guía** se agregan distinto: se suben a Supabase Storage y se pega el link en el panel de Admin (dentro de la web, no aquí en GitHub). Cuando tengas listo el catálogo, avísame para activar el Storage de Supabase.
