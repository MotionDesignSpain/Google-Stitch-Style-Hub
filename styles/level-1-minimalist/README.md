🟢 Estilo: Pure Minimal
========================

**Nivel:** Sencillo (Level 1)
**Archivo CSS:** `theme-minimal.css`
**JavaScript:** 0 líneas (CSS-Only)

> Diseño limpio, ligero y estructural. La base ideal para cualquier proyecto. Bordes sutiles, máximo espacio en blanco y tipografía legible.

## 🎨 Demo Interactiva

> 👉 **[Ver demo completa en vivo →](../../docs/demos/pure-minimal.html)**

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
| `Primary` | `#1a73e8` | Google Blue |
| `Background` | `#ffffff` | Blanco puro |
| `Surface` | `#f8f9fa` | Gris suave |
| `Border` | `#e0e0e0` | Gris borde |
| `Text` | `#202124` | Negro Google |

## 💻 Características del Diseño

1. **Bordes Sutiles:** Contenedores con `border: 1px solid` apenas visibles que delimitan sin saturar.
2. **Espacio en Blanco Generoso:** Amplios paddings y margins para una lectura cómoda.
3. **Flat Design Puro:** Sin sombras, sin elevaciones. La jerarquía se define solo con tipografía y espaciado.
4. **Google Sans Ready:** Preparado para la tipografía del ecosistema Google.

## 🎯 Ideal Para

Herramientas internas, prototipos rápidos, documentación, MVPs donde la velocidad prima sobre la estética.

## 🚀 Uso Rápido

1. Copia `theme-minimal.css` a tu directorio de estilos
2. Enlázalo en tu HTML: `<link rel="stylesheet" href="theme-minimal.css">`
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
