🎮 Estilo: Playful 3D
======================

**Nivel:** Gamification (Level 6)
**Archivo CSS:** `theme-playful.css`
**JavaScript:** 0 líneas (CSS-Only)

> Estilo táctil y divertido basado en Duolingo y Discord. Botones apretables con física realista, curvas grandes y colores alegres.

## 🎨 Demo Interactiva

> 👉 **[Ver demo completa en vivo →](../../docs/demos/playful-3d.html)**

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
| `Primary` | `#1cb0f6` | Azul Duolingo |
| `Success` | `#58cc02` | Verde acción |
| `Danger` | `#ff4b4b` | Rojo alerta |
| `Surface` | `#ffffff` | Blanco |
| `Border` | `#e5e7eb` | Gris suave |

## 💻 Características del Diseño

1. **Botones 3D Físicos:** `border-bottom: 6px solid` que colapsa al `:active`, simulando un botón real.
2. **Curvas Generosas:** `border-radius: 16px+` para una apariencia amigable y táctil.
3. **Colores Alegres Saturados:** Paleta vibrante tipo Duolingo con verdes, azules y rojos brillantes.
4. **Feedback Háptico Visual:** Transiciones `transform` que simulan la sensación de 'apretar' un botón.

## 🎯 Ideal Para

Apps educativas, gamificación, herramientas para niños/jóvenes, onboarding divertido, aplicaciones sociales.

## 🚀 Uso Rápido

1. Copia `theme-playful.css` a tu directorio de estilos
2. Enlázalo en tu HTML: `<link rel="stylesheet" href="theme-playful.css">`
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
