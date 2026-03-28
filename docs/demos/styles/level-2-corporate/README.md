🏢 Estilo: Corporate Elegance
==============================

**Nivel:** Profesional (Level 2)
**Archivo CSS:** `theme-corporate.css`
**JavaScript:** 0 líneas (CSS-Only)

> Diseño profesional orientado a paneles de administración, aplicaciones financieras o médicas. Jerarquía visual basada en elevación y sombras.

## 🎨 Demo Interactiva

> 👉 **[Ver demo completa en vivo →](../../docs/demos/corporate.html)**

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
| `Primary` | `#1a73e8` | Azul Zafiro |
| `Background` | `#f4f5f7` | Gris corporativo |
| `Surface` | `#ffffff` | Blanco |
| `Border` | `#dfe1e6` | Gris borde |
| `Text` | `#172b4d` | Azul oscuro |

## 💻 Características del Diseño

1. **Iluminación Profunda:** Los contenedores se separan del fondo usando sutiles sombras estáticas.
2. **Interactividad Táctil:** Al hacer hover, los contenedores 'flotan' con `translateY(-2px)` y ampliación de sombra.
3. **Contrastes Azules:** Tonos basados en azul zafiro en lugar de negro puro.
4. **Elevaciones por Capas:** Z-index y sombras definen la importancia visual de cada componente.

## 🎯 Ideal Para

Paneles de administración, dashboards financieros, aplicaciones médicas, herramientas empresariales SaaS.

## 🚀 Uso Rápido

1. Copia `theme-corporate.css` a tu directorio de estilos
2. Enlázalo en tu HTML: `<link rel="stylesheet" href="theme-corporate.css">`
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
