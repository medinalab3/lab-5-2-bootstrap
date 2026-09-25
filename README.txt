PROYECTO: Creación de una página web responsiva con Bootstrap y CSS
CURSO: NCBTO - 2026-5CC - WADE 1000L - 3663ONL (Front-End Technologies and
       User Interface (UI) and Laboratory)
UNIVERSIDAD: Northbridge University
ESTUDIANTE: Gerardo J. Medina (GJ)
NUMERO DE ESTUDIANTE: 2507056253

DESCRIPCIÓN
-----------
Este proyecto es la continuación de los laboratorios de los Módulos 3 y 4
(estructura HTML/HTML5 y CSS propio), ahora aplicando los conceptos del
Módulo 5 sobre el framework CSS Bootstrap. La página fue construida en
Visual Studio Code y gestionada con control de versiones (Git/GitHub).
Demuestra el uso de:

1. Estructura HTML y semántica de los Módulos 3 y 4: <header>, <nav>,
   <main>, <section>, <article>, <footer>.

2. Integración del framework Bootstrap (vía CDN) en la página ya creada,
   agregando su hoja de estilos y su JavaScript.

3. Estilos del framework Bootstrap:
   - Selectores/clases de Bootstrap (ej. .navbar, .card, .btn, .form-control,
     .row, .col-md-6) que traen ya definidas sus propias reglas de CSS.
   - Propiedades de Bootstrap aplicadas mediante esas clases (colores,
     espaciado, bordes redondeados, sombras, tipografía).

4. Selectores CSS propios (además de los de Bootstrap):
   - De elemento (ej. body, footer).
   - De ID (ej. #titulo-hero, #menu-principal, #miLienzo) para estilos
     únicos en partes específicas de la página.
   - De clase (ej. .tarjeta-destacada) para reutilizar un estilo propio
     en varios elementos.

5. Modelo de caja (box model): la clase propia "tarjeta-destacada"
   sobrescribe el padding, borde y sombra de una tarjeta de Bootstrap en
   particular, mostrando cómo se puede personalizar el modelo de caja
   incluso trabajando sobre un framework.

6. Diseño responsivo: el grid de 12 columnas de Bootstrap (row / col-md-*)
   adapta automáticamente el contenido a distintos tamaños de pantalla, y
   se complementa con una media query propia (@media max-width: 576px)
   para ajustes adicionales en celulares.

7. Interfaz de usuario básica con Bootstrap: barra de navegación (navbar)
   con menú colapsable en móvil, tarjetas (cards) para los proyectos, y
   un formulario de contacto (form-control, btn) con estilos ya listos
   del framework.

8. Variedad de componentes de Bootstrap para un diseño atractivo y
   funcional: navbar, hero con degradado, grid responsivo, cards,
   list-group, botones (btn-primary, btn-outline-primary) y formulario.

ARCHIVOS INCLUIDOS
-------------------
- index 5.1.html   -> Estructura de la página con Bootstrap integrado y
                       comentarios explicativos.
- style.css        -> Hoja de estilos propia (selectores, modelo de caja
                       y ajustes responsivos), cargada después de Bootstrap.
- imagenes/        -> Carpeta con la captura del proyecto.
- audio/           -> Carpeta con el archivo de audio de prueba.
- videos/          -> Carpeta con el archivo de video de prueba.
- README.txt       -> Este archivo.

ENLACE DEL REPOSITORIO DE GITHUB
---------------------------------
https://github.com/medinalab3/lab-4-2-css-estilos

CÓMO VISUALIZAR EL PROYECTO
-----------------------------
1. Abrir la carpeta del proyecto en Visual Studio Code.
2. Abrir el archivo "index 5.1.html" con la extensión Live Server (Bootstrap
   se carga desde internet vía CDN, así que se necesita conexión a internet
   para ver los estilos) o directamente con el navegador de preferencia.
3. Para probar el diseño responsivo, abrir las herramientas de
   desarrollador (F12), activar la vista de dispositivo móvil, o reducir
   el ancho de la ventana y observar cómo el menú de navegación se
   colapsa en un botón de hamburguesa y las tarjetas se apilan.
