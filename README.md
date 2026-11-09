# Portafolio web — Maia Sofia Ospina Moncayo

Sitio estático responsive construido con HTML, CSS y JavaScript vanilla. No requiere framework, compilación ni dependencias de npm.

## Archivos
- `index.html`: estructura y contenido del sitio.
- `styles.css`: diseño visual, responsive y accesibilidad de movimiento reducido.
- `script.js`: menú móvil, navegación activa y año automático del footer.
- `assets/maia-profile.jpg`: fotografía extraída de la hoja de vida suministrada.

## Probar localmente
Abre `index.html` en un navegador. Para una prueba local más fiel a producción, ejecuta desde esta carpeta:

```bash
python3 -m http.server 8000
```

Luego visita `http://localhost:8000`.

## Publicar
Sube el contenido completo de esta carpeta a cualquier hosting estático (Netlify, Vercel, GitHub Pages o el servidor de tu organización). Mantén la carpeta `assets` junto a `index.html` para que cargue la fotografía.

## Antes de publicar
- Confirma que deseas mostrar públicamente los dos correos y el número telefónico incluidos en la hoja de vida.
- Si tienes una URL de portafolio, LinkedIn o proyectos audiovisuales, puedes añadirla a la navegación o a la sección de contacto.
- El contenido refleja la hoja de vida adjunta. No se añadió una experiencia empresarial independiente porque el documento no la detalla.

## Personalización rápida
Los colores principales están definidos como variables al inicio de `styles.css` (`--navy`, `--blue`, `--steel`, `--mist`). Los textos y enlaces se editan directamente en `index.html`.
