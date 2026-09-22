# Defectos y Mejoras - Proyecto Calculadora

Este documento detalla la auditoría realizada al código inicial, identificando los defectos encontrados y las soluciones aplicadas para estandarizar el proyecto.

| N° | Defecto Identificado | Archivo Afectado | Solución Aplicada / Corrección |
| :--- | :--- | :--- | :--- |
| **1** | Nombres de archivos con espacios y mayúsculas | `Mi Pagina De Notas.HTML` | Renombrado a minúsculas y sin espacios (`index.html`) |
| **2** | Extensiones y nombres de estilos inadecuados | `Estilo Del Sitio.CSS` | Renombrado a formato estándar (`styles.css`) |
| **3** | Falta de control de versiones y flujo de trabajo | Repositorio | Creación de ramas `dev`, `pruebas` y `feature/correcciones` |
| **4** | Ausencia de atributos de accesibilidad/asociación | `index.html` | Vinculación correcta de etiquetas mediante el atributo `for` |
| **5** | Variables y funciones con nombres poco descriptivos | `index.html` | Refactorización a nombres claros y estándar (`calcularPromedio`) |
| **6** | Estilos o selectores CSS genéricos y desorganizados | `styles.css` | Optimización de clases semánticas y formato visual |
| **7** | Código desindentado o falta de semántica en etiquetas | `index.html` | Limpieza general, indentación y uso correcto de etiquetas HTML |
| **8** | Falta de documentación técnica inicial | Raíz del proyecto | Creación y estructuración del archivo `README.md` con hallazgos |