🦇 Estilo: Monochrome Stealth
==============================

**Nivel:** Stealth (Level 5)
**Archivo CSS:** `theme-monochrome.css`
**JavaScript:** 0 líneas (CSS-Only)

> Minimalismo oscuro técnico. Fondo negro puro, sin sombras, bordes de 1px y tipografía monospace. Inspirado en Vercel, Linear y herramientas DevTool.

## 🎨 Demo Interactiva

> 👉 **[Ver demo completa en vivo →](../../docs/demos/monochrome.html)**

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
| `Primary` | `#ededed` | Blanco brillante |
| `Success` | `#0df0ab` | Teal digital |
| `Accent` | `#0070f3` | Azul Vercel |
| `Background` | `#000000` | Negro puro |
| `Border` | `#333333` | Gris acero |

## 💻 Características del Diseño

1. **Negro Absoluto:** `background: #000` sin gradientes ni texturas. Máximo contraste.
2. **Sin Sombras:** Todo se define por bordes de 1px precisos. Nada de blur o box-shadow.
3. **Monospace Nativo:** Tipografía `monospace` para una estética de terminal/DevTool.
4. **Dark Theme Nativo:** Overrides específicos para que todos los componentes Pro sean visibles sobre fondo negro.

## 🎯 Ideal Para

Herramientas de desarrollo, CLIs web, dashboards técnicos, aplicaciones estilo Vercel/Linear/Raycast.

## 🚀 Uso Rápido

1. Copia `theme-monochrome.css` a tu directorio de estilos
2. Enlázalo en tu HTML: `<link rel="stylesheet" href="theme-monochrome.css">`
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
