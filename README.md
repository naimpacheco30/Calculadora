# Taller Integrador Individual - Cortes 1 y 2
Estudiante: Naim Pacheco

# Enlace al sitio publicado
https://calucalodorpromedios.netlify.app

# Tabla de Hallazgos de la Auditoría

| Defecto encontrado | Por qué era un problema | Cómo lo corrigió |
| :--- | :--- | :--- |
| **Nombres de archivos con espacios y mayúsculas** (`Mi Pagina De Notas.HTML`) | Impide el correcto funcionamiento en servidores web y rompe los estándares multiplataforma. | Se renombraron a minúsculas y sin espacios (`index.html` y `styles.css`). |
| **Variable o función con nombres poco descriptivos** | No indica qué almacena o procesa; obliga a leer todo el código para entenderlo. | Se refactorizaron a nombres claros y descriptivos (`calcularPromedio`, `nota1`). |
| **Ausencia de asociación en etiquetas** | Afecta la accesibilidad web y la usabilidad de los campos de entrada. | Se enlazaron correctamente usando los atributos `for` correspondientes en el HTML. |
| **Estilos CSS genéricos y desorganizados** | Dificulta el mantenimiento y la escalabilidad de las hojas de estilo del sitio. | Se estructuraron clases semánticas claras (`.contenedor-principal`). |
| **Falta de historial de commits estructurados** | No permite trazar los cambios ni identificar qué aportó cada modificación. | Se implementó el uso de commits formales con prefijos obligatorios (`chore`, `refactor`, `style`, `docs`). |
| **Estructura de ramas incorrecta en el flujo** | Trabajar directamente sobre ramas principales sin aislar las correcciones rompe buenas prácticas. | Se desarrolló el trabajo en una rama `feature/correcciones` para fusionar mediante Pull Request hacia `dev`. |
| **Falta de documentación inicial en el repositorio** | El proyecto carece de contexto, instrucciones y reporte de auditoría para su revisión. | Se creó y estructuró el archivo `README.md` detallando las correcciones. |
| **Ausencia de pie de página institucional** | El sitio carece de identidad y metadatos de autoría corporativa. | Se añadió un bloque `<footer>` con el sello institucional respectivo. |
