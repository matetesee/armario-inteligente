# matetesee — Estilo JB (versión castellano)

Quiz funnel de venta clonado y traducido al castellano a partir de `quiz.estilojb.com.br`.
Producto: **150 Looks con 15 Prendas — El Manual de las Combinaciones Inteligentes**.

## Antes de usarlo en producción
- Reemplazá `CHECKOUT_URL` dentro de `index.html` (bloque `CONFIG`) por el link real de checkout (Hotmart u otro).
- Las imágenes se sirven desde el CDN original (`inlead.cloud`). Si en algún momento se pierde ese acceso, conviene re-hostear los assets.

## Correr local
```bash
npm start
```
Sirve en `http://localhost:3000` (o el puerto que indique `$PORT`).

## Deploy
Desplegado en Railway (team NativeAnalyzer).
