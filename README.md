# N.A Landing

Landing estática de servicios técnicos, enfocada en conversión por WhatsApp.

## Estructura

- `index.html`: estructura de la landing.
- `styles.css`: estilos, layout y carrusel.
- `assets/img/`: imágenes y video real de trabajos.
- `vercel.json`: configuración para despliegue en Vercel.
- `PROJECT.md`: alcance funcional y decisiones del proyecto.

## Estado actual

- Sitio funcional en Netlify para iteración.
- Carrusel horizontal de trabajos con imágenes reales y soporte de video.
- CTA principales orientados a WhatsApp.
- Copy ajustado a tono técnico y cercano.

## Ejecutar local

```powershell
cd C:\Users\Lucas\Documents\olanda\na-landing
python -m http.server 5500
```

Abrir: `http://localhost:5500`

## Iteración actual

- Mantener URLs sociales genéricas temporalmente.
- Corregido bug de video que se salía del marco del carrusel.
- Optimización ligera de carga con `loading="lazy"`, `decoding="async"` y `preload="metadata"` en video.

## Deploy

### Netlify (iteración)

```powershell
npx netlify deploy --prod --dir=.
```

### Vercel (final)

Se publicará al final de la iteración con URLs definitivas y dominio comprado.
