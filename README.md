# Pendientes del negocio

Una sola página web (HTML) sin servidor propio, sin Firebase y sin instalar nada.
Los datos se guardan en el móvil (funciona sin internet) y se sincronizan entre los dos socios mediante
un "espacio" gratuito en jsonblob.com.

## Publicar en GitHub (sin comandos)
1. Entra en https://github.com → **New repository** (nombre p. ej. `pendientes`) → **Create repository**.
2. **uploading an existing file** → arrastra los 5 archivos: `index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png` → **Commit changes**.
3. **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root) → Save**.
4. En ~1 minuto estará en `https://TU-USUARIO.github.io/pendientes/`.

## Usarla
1. Abre esa dirección en tu móvil → pon tu nombre → **Crear espacio nuevo**.
2. Pulsa **Compartir** y envía el enlace a tu socio. Al abrirlo, pone su nombre y **Entrar**.
3. Instálala: Android (Chrome) menú ⋮ → *Instalar aplicación*; iPhone (Safari) Compartir → *Añadir a pantalla de inicio*.

## Importante
- Quien tenga el enlace puede ver y editar las tareas: no lo publiques.
- Los datos se refrescan cada 5 segundos mientras la app está abierta.
- jsonblob.com borra espacios sin uso durante 75 días; si pasara, pulsa el aviso rojo y se recrea con los datos del móvil.
