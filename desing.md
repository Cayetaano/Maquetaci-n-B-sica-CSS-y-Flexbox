## 1. Filosofía de Diseño

Diseño minimalista, moderno y limpio enfocado en la usabilidad y la tipografía clara. Se prioriza el contraste oscuro (Dark Mode), la separación mediante espacios en blanco (_white space_) y el uso estricto de Flexbox para la distribución de layouts.

## 2. Colores

- **Fondo principal (`--bg-color`)**: `#0b0b0c` (Oscuro mate)
- **Fondo de contenedores (`--card-bg`)**: `#161618` (Gris oscuro elevado)
- **Texto principal (`--text-color`)**: `#f5f5f7` (Blanco suave)
- **Texto secundario (`--text-muted`)**: `#86868b` (Gris medio)
- **Acento principal (`--accent-color`)**: `#2997ff` (Azul tech tipo Apple)
- **Bordes y separadores (`--border-color`)**: `#2d2d30`

## 3. Tipografía e Iconografía

- **Fuente Principal**: 'Inter', sans-serif (importada vía Google Fonts CDN).
- **Iconos**: Font Awesome 6 (importados vía CDN).

## 4. Estructura y Maquetación

- **Contenedor global**: Ancho dinámico fluido entre `1000px` (min-width) y `2000px` (max-width).
- **Layout**: Uso del modelo Flexbox para alineación vertical y horizontal en cabecera, cuadrículas de contenido y pie de página.
- **Posicionamiento**: Botón flotante de acción fija (`position: fixed`) en la esquina inferior derecha.
