# Investigación: Uso de Markdown en el Desarrollo de Software y GitHub

## 1\. ¿Qué es Markdown?

Markdown es un **lenguaje de marcado ligero** creado por John Gruber en 2004. A diferencia de los procesadores de texto tradicionales (como Microsoft Word) o lenguajes de código complejos (como HTML), Markdown permite dar formato al texto utilizando caracteres simples de puntuación.

Su filosofía principal es la **legibilidad**: el objetivo es que un documento escrito en Markdown sea fácil de leer y escribir tal cual, sin parecer que está lleno de etiquetas o instrucciones de formateo complejas.

## 2\. ¿Por qué se usa en proyectos de software?

En la industria del desarrollo de software, Markdown se ha convertido en el estándar *de facto* para la documentación por tres razones principales:

* **Compatibilidad con Control de Versiones (Git):** Al ser archivos de **texto plano**, herramientas como Git pueden rastrear cambios línea por línea de manera eficiente. Si se usara un archivo binario, Git no podría mostrar las diferencias entre versiones.
* **Velocidad y Flujo de Trabajo:** Los desarrolladores pueden escribir documentación sin necesidad de levantar las manos del teclado para buscar botones de formato en una interfaz gráfica, lo que agiliza el proceso.
* **El Estándar README.md:** Es la carta de presentación de casi cualquier repositorio de código abierto. Explica qué hace el software, cómo instalarlo y cómo contribuir. La extensión .md indica al sistema que debe renderizar el archivo usando este lenguaje.

## 3\. Relación con GitHub (GitHub Flavored Markdown)

GitHub popularizó masivamente este lenguaje. Cuando se sube un archivo llamado `README.md` a un repositorio, GitHub lo procesa automáticamente para mostrarlo como una página web formateada en la portada del proyecto.

GitHub creó su propia versión extendida llamada **GFM (GitHub Flavored Markdown)**, que añade funcionalidades críticas para los programadores que el Markdown original no tenía:

* **Resaltado de sintaxis:** Colorea bloques de código según el lenguaje (Python, JavaScript, C++, etc.).
* **Tablas:** Permite organizar datos en filas y columnas de forma sencilla.
* **Listas de tareas:** Crea casillas de verificación interactivas.
* **Referencias automáticas:** Permite enlazar a otros "issues", "pull requests" o usuarios.

## 4\. Ventajas y Desventajas

### Ventajas

* **Curva de aprendizaje mínima:** La sintaxis básica se puede aprender en menos de 10 minutos.
* **Portabilidad:** Un archivo `.md` se puede abrir en cualquier editor de texto (Notepad, VS Code, Vim) y siempre será legible, independientemente del sistema operativo.
* **Ligereza:** Los archivos ocupan muy poco espacio (kilobytes).
* **Versatilidad:** Se puede convertir fácilmente a HTML, PDF, EPUB o diapositivas.

### Desventajas

* **Falta de estandarización estricta:** Existen muchos "sabores" (CommonMark, MultiMarkdown, GFM), lo que a veces provoca que una tabla o elemento complejo se vea bien en una aplicación pero mal en otra.
* **Limitaciones de diseño:** No ofrece control preciso sobre el diseño visual (márgenes, tipografías específicas, colores de fondo) a menos que se incruste código HTML/CSS, lo cual reduce la legibilidad.
* **Manejo de imágenes:** Redimensionar o alinear imágenes (centro, derecha, izquierda) suele requerir etiquetas HTML adicionales, ya que Markdown nativo no lo soporta directamente.
