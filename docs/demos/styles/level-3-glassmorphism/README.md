🟣 Estilo: Glass & Gradients
=============================

**Nivel:** Avanzado (Level 3)
**Archivo CSS:** `theme-glass.css`
**JavaScript:** 0 líneas (CSS-Only)

> Diseño vibrante de alto impacto estético. Cajas cristal translúcidas con backdrop-filter, gradientes oscuros y acentos neón.

## 🎨 Demo Interactiva

> 👉 **[Ver demo completa en vivo →](../../docs/demos/glassmorphism.html)**

## 🏗️ Arquitectura de Componentes (13 Secciones)

Este tema comparte la misma arquitectura que los demás niveles.
La IA lee este índice al inicio del CSS y sabe exactamente qué clases usar:

```
 0. Variables Globales (:root)
 1. Bases Estructurales (.stitch-container, .stitch-section-title)
 2. Tipografía Semántica (.stitch-h1, .stitch-body)
 3. Botones y Acciones (.stitch-btn, .stitch-btn-primary)
 4. Formularios y Controles (.stitch-input, .stitch-toggle, .stitch-range)
 5. Feedback Visual (.stitch-badge, .stitch-avatar, .flex-row)
 6. Progress & Listas (.stitch-progress-wrapper, .stitch-list)
 7. Estructuras de Datos (.stitch-card, .stitch-table, .stitch-tabs)
 8. Componentes Avanzados CSS-Only (.stitch-skeleton, .stitch-tooltip, .stitch-carousel)
 9. Grid Layout (.stitch-grid, .stitch-col-span-*)
10. Navegación Avanzada (.stitch-breadcrumb, .stitch-dropdown)
11. Data-Viz (.stitch-bar-chart, .stitch-donut, .stitch-timeline)
12. Feedback Pro (.stitch-toast, .stitch-empty-state, .stitch-steps)
13. Formularios Pro (.stitch-input-icon-wrapper, .stitch-chips-input, .stitch-dropzone)
```

## 🎨 Paleta de Colores

| Variable | Valor | Descripción |
|----------|-------|-------------|
| `Primary` | `#ec4899` | Rosa Neón |
| `Accent` | `#8b5cf6` | Púrpura |
| `Glass BG` | `rgba(255,255,255,0.03)` | Cristal translúcido |
| `Glass Border` | `rgba(255,255,255,0.1)` | Borde cristal |
| `Text` | `#ffffff` | Blanco puro |

## 💻 Características del Diseño

1. **Glassmorphism Auténtico:** `backdrop-filter: blur(16px)` con fondos `rgba()` translúcidos.
2. **Gradientes Oscuros:** Fondo base con gradientes profundos que aportan profundidad.
3. **Neones Sutiles:** Acentos rosa y púrpura que brillan sobre fondo oscuro.
4. **Dark Theme Nativo:** Overrides específicos para que todos los componentes Pro sean visibles en fondo oscuro.

## 🎯 Ideal Para

Landing pages premium, portfolios creativos, aplicaciones de música/streaming, herramientas de diseño.

## 🚀 Uso Rápido

1. Copia `theme-glass.css` a tu directorio de estilos
2. Enlázalo en tu HTML: `<link rel="stylesheet" href="theme-glass.css">`
3. Usa las clases `.stitch-*` documentadas en el Índice Maestro
4. Dale el CSS a tu IA como contexto para que genere HTML compatible

```html
<div class="stitch-container">
    <span class="stitch-section-title">Mi Sección</span>
    <h1 class="stitch-h1">Título Principal</h1>
    <p class="stitch-body">Contenido estructurado.</p>
    <div class="stitch-grid stitch-grid-3">
        <div class="stitch-card">
            <div class="stitch-card-body">Columna 1</div>
        </div>
        <div class="stitch-card stitch-col-span-2">
            <div class="stitch-card-body">Columna 2-3</div>
        </div>
    </div>
</div>
```

---

📐 **Metodología Stitch:** Estructura HTML → Aprobación → Inyección funcional.
Consulta el [README principal](../../README.md) para más detalles.
