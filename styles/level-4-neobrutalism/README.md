🟨 Estilo: Neo-Brutalism
=========================

**Nivel:** Experimental (Level 4)
**Archivo CSS:** `theme-brutal.css`
**JavaScript:** 0 líneas (CSS-Only)

> Estilo audaz y de altísimo contraste. Bordes gruesos, sombras sólidas sin desenfoque y colores primarios saturados. Inspirado en Figma/Gumroad.

## 🎨 Demo Interactiva

> 👉 **[Ver demo completa en vivo →](../../docs/demos/neo-brutalism.html)**

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
| `Primary` | `#a855f7` | Púrpura brillante |
| `Secondary` | `#fde047` | Amarillo póster |
| `Accent` | `#06b6d4` | Cian/Celeste |
| `Border` | `#000000` | Negro total |
| `Background` | `#f4f4f0` | Off-white papel |

## 💻 Características del Diseño

1. **Sombras Sólidas:** `box-shadow: 5px 5px 0px #000` sin desenfoque alguno. Estilo póster retro.
2. **Bordes Gruesos (3px):** Todos los contenedores, inputs y tarjetas llevan bordes negros pesados.
3. **Física del Clic:** Al hacer hover/clic, los elementos se desplazan (`translate`) simulando que se 'aprietan contra la pared'.
4. **Tipografía Impactante:** Weight 800-900, `text-transform: uppercase`, `-webkit-text-stroke`.

## 🎯 Ideal Para

Apps creativas, herramientas de productividad alternativa, landing pages de startups, portfolios artísticos.

## 🚀 Uso Rápido

1. Copia `theme-brutal.css` a tu directorio de estilos
2. Enlázalo en tu HTML: `<link rel="stylesheet" href="theme-brutal.css">`
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
