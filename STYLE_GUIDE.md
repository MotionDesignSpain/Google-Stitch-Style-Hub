# Manifiesto de Estilos (Style Manifesto) 📜✨

¡Hola, creador! Todo componente o utilidad visual que se añada a **Google Stitch Styles** debe cumplir con nuestro estándar de calidad. Este estándar garantiza que cualquier desarrollador o diseñador que use tus estilos pueda entenderlos y aplicarlos en su proyecto en segundos.

Para que un nuevo estilo sea **aceptado** en el repositorio, la documentación de tu contribución o tu Pull Request debe incluir *obligatoriamente* los siguientes tres elementos:

---

## 1. 📝 Snippet de código listo para copiar

El objetivo es que sea "plug-and-play" (conectar y usar). Debes proporcionar el bloque exacto de HTML con las clases necesarias para que el usuario pueda copiar, pegar y ver el resultado trabajando inmediatamente.

**Ejemplo de lo que esperamos:**
```html
<!-- Ejemplo: Tarjeta de perfil básica -->
<div class="stitch-card stitch-card-elevated">
  <img src="..." class="stitch-avatar" alt="Avatar">
  <div class="stitch-card-content">
    <h3 class="stitch-typography-h3">Título de la Tarjeta</h3>
    <p class="stitch-text-muted">Descripción breve de la tarjeta.</p>
  </div>
</div>
```

## 2. 🎛️ Variables personalizables (Design Tokens)

Nuestro sistema es ultra-flexible. Si tu componente tiene propiedades que un proyecto podría querer ajustar (como un color de borde, un grosor específico o una sombra), debes usar y listar explícitamente qué variables CSS (Tokens) lo controlan.

**Ejemplo de lo que esperamos:**
*   `--stitch-card-border-color`: Define el color del borde sutil de la tarjeta.
*   `--stitch-card-radius`: Define la curvatura de las esquinas (usa nuestros tokens de *shape*, ej. `var(--stitch-shape-radius-md)`).
*   `--stitch-card-bg`: Fondo de la tarjeta (por defecto `var(--stitch-color-surface)`).

## 3. 📸 Captura de pantalla del resultado

Una imagen vale más que mil líneas de código. Para aceptar un estilo, necesitamos tener la certeza visual de cómo luce en el navegador antes de implementarlo ciegamente. 

**Ejemplo de lo que esperamos:**
Sube siempre una imagen (`.png`, `.jpg`) o un pequeño `.gif` (si el elemento tiene animaciones, estado `:hover`, o `:active`) mostrando claramente el diseño final de tu componente renderizado.
```markdown
![Ejemplo visual de la tarjeta de perfil renderizada](./ruta/a/tu/imagen/tarjeta-demo.png)
```

---

¡Gracias por velar por la calidad visual de la herramienta! Si tu aportación cumple con este manifiesto, ¡su integración al repositorio principal será rápida y segura! 🚀
