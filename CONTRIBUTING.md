# ¡Bienvenido a la Guía de Contribución de Estilos de Google Stitch! 🎉

¡Hola! Estamos encantados de que estés aquí. Gracias por tu interés en contribuir a nuestro repositorio de estilos y documentación para **Google Stitch**. Este proyecto prospera gracias a la colaboración, y tu ayuda es fundamental para que nuestras interfaces sean más consistentes, hermosas y accesibles para todos.

No importa si eres un desarrollador frontend Senior, un diseñador hiper-detallista, o si es tu primera vez contribuyendo a un repositorio: **¡tu aporte es inmensamente valioso!** Hemos creado esta guía para que tu experiencia colaborando sea fluida, segura y agradable.

---

## 🐛 Reportar Errores (Bugs)

¿Viste un estilo que no se renderiza correctamente, un color fuera de lugar o un componente que falla en móvil? ¡Ayúdanos a solucionarlo! 
Para reportar un error, por favor abre un _Issue_ y trata de incluir la siguiente información:
- **Descripción clara:** Qué esperabas que sucediera vs. qué sucedió realmente.
- **Pasos para reproducir:** Cómo podemos nosotros ver el error por nuestra cuenta.
- **Capturas de pantalla o videos:** Si es un problema visual, una imagen nos ayudará muchísimo a entender el problema exacto.
- **Entorno:** Cuéntanos qué navegador, sistema operativo y tamaño de pantalla estabas usando.

## 💡 Sugerir Mejoras y Nuevas Características

¿Tienes una idea para un nuevo estilo, una utilidad CSS innovadora o una mejora en cómo explicamos algo en la documentación? ¡Nos encantaría implementarla contigo!
- Abre un _Issue_ y etiquétalo como "Feature Request".
- Explica el **por qué** y el **cómo**: ¿Qué problema de diseño o desarrollo resuelve tu sugerencia? ¿Cómo beneficiaría a la comunidad de Google Stitch?
- Si tienes ejemplos visuales, prototipos o referencias de diseño de usabilidad, ¡inclúyelos!

## 🚀 Cómo Crear un Pull Request (PR)

¡Estamos listos para ver tu código mágico! Sigue estos pasos para enviar tu trabajo constructivo:

1. **Haz un Fork** del repositorio y clónalo en tu entorno local.
2. **Crea una rama (branch)** para tu contribución, usando nombres descriptivos: `git checkout -b feature/nuevo-estilo-tarjetas` o `fix/reparacion-margen-boton`.
3. **Haz tus cambios** siguiendo nuestras pautas de estilo descritas más abajo.
4. **Prueba visual y funcionalmente:** Asegúrate de que tus cambios se vean perfectos en múltiples resoluciones (móvil, tablet, escritorio).
5. **Haz Commit** con mensajes claros: `feat: añade estilo primario para notificaciones` o `docs: mejora la guía de tipografía`.
6. **Sube tus cambios** (Push) a tu fork y ¡abre un Pull Request hacia nuestra rama `main`!
7. **Revisión constructiva:** Un mantenedor de nuestro equipo revisará tu código. Estamos aquí para ayudarte, así que te daremos retroalimentación amable para asegurarnos de que el código esté listo antes de fusionarlo.

## 🎨 Pautas de Estilo y Documentación

Para mantener un ecosistema cohesivo y que el mantenimiento sea sencillo, te pedimos que sigas estas convenciones:

### Estilos de Diseño (CSS / SCSS)
- **Nomenclatura semántica:** Utiliza convenciones claras para nombrar clases. Nuestros selectores deben describir su propósito (ej. `.stitch-btn-primary`) y ser independientes de en qué página se encuentren.
- **Tokens de Diseño siempre:** Usa siempre los Design Tokens de Google Stitch (variables CSS) para colores, fuentes, espaciados y sombras en lugar de valores 'duros'. (ej. usa `var(--stitch-color-blue-500)` en lugar de `#4285F4`).
- **Simplicidad ante todo:** Escribe estilos modulares que se puedan reutilizar como legos. Evita profundamente el uso de `!important` a menos que no exista otra salida arquitectónica.

### Guías de Documentación
- **Claridad acogedora:** Escribe en un tono profesional, claro y amistoso.
- **Ejemplos Inclusivos:** Siempre que documentes un estilo, incluye ejemplos de código (HTML/CSS) demostrando cómo usarlo.
- **Estados Completos:** Al añadir o mejorar un componente visual, asegúrate de documentar cómo se ve en sus diferentes estados interactivos: `hover`, `active`, `focus` (por accesibilidad) y `disabled`.

¡Gracias nuevamente por dedicar tu tiempo y talento! Juntos hacemos que Google Stitch sea una herramienta de diseño excepcional. ❤️
