# Marca personal — Danna Moreno

Sitio web estático responsive construido con HTML, CSS y JavaScript vanilla. No requiere framework ni proceso de compilación.

## Archivos
- `index.html`: estructura y contenido.
- `styles.css`: diseño visual, responsive y estados.
- `script.js`: menú móvil, filtros de proyectos y año automático.

## Probar localmente
Abre `index.html` en un navegador o ejecuta un servidor local desde esta carpeta:

```bash
python3 -m http.server 8000
```

Luego visita `http://localhost:8000`.

## Antes de publicar
1. Reemplaza `TU_CORREO@EJEMPLO.COM` por tu correo profesional en `index.html` (en el enlace `mailto:` y el texto visible).
2. Sustituye los enlaces genéricos de LinkedIn e Instagram por tus perfiles.
3. Completa la sección de experiencia / emprendimiento con cargos, organizaciones, fechas y resultados reales. No se inventaron experiencias empresariales.
4. Revisa títulos, fechas y descripciones de los proyectos; añade enlaces, fotografías o piezas finales cuando estén disponibles.
5. Si quieres usar dominio propio, configura el DNS de tu proveedor de hosting para apuntar al despliegue.

## Despliegue
Puedes publicar directamente esta carpeta en cualquier hosting estático (por ejemplo, GitHub Pages, Netlify, Vercel o el hosting de tu dominio). No necesita backend.

## Personalización
- Colores: variables CSS al inicio de `styles.css`.
- Tipografías: importación de Google Fonts en `index.html`; hay fuentes de respaldo.
- Proyectos: duplica un bloque `.project-card` y asigna `data-category` (`periodismo`, `investigacion` o `audiovisual`); añade el filtro correspondiente si creas una categoría nueva.

## Nota de producción
El formulario de contacto no se ha simulado: se ofrece un enlace `mailto:` para que el sitio funcione sin backend. Si necesitas un formulario real, integra un servicio de formularios o una API y añade protección antispam.
