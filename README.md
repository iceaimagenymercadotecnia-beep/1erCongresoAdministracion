# Dashboard - 1.º Congreso de Estudiantes de Administración

Etapa 1 del sitio para GitHub Pages. En esta versión se publica la convocatoria y se prioriza el registro de propuestas antes del cierre del 19 de septiembre de 2026.

## Estructura
- `index.html`: interfaz principal.
- `styles.css`: identidad visual y diseño responsivo.
- `app.js`: navegación, carga de datos, programa, búsqueda/filtros, Mi Agenda y detalles.
- `data/evento.json`: única fuente lógica de datos variables del evento en esta etapa.
- `assets/`: convocatoria PDF e imágenes proporcionadas.

## Publicación en GitHub Pages
Sube el contenido de esta carpeta a la raíz del repositorio y activa GitHub Pages desde la rama correspondiente. No requiere compilación ni dependencias.

## Actualización cuando llegue el programa maestro
No rediseñar el sitio. Convertir el Excel maestro a registros estructurados en `data/evento.json` (campo `programa`) conservando exactamente folios, títulos, autores, fechas, horarios, modalidad, sede, responsables y enlaces. Todas las vistas se alimentan del mismo arreglo.

## Estado actual
El comité aún no ha proporcionado el programa general. Por ello `programa` está vacío y el sitio muestra explícitamente que está en preparación. No se inventaron registros provisionales.
