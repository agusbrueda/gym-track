GYM TRACK — PWA para iPhone

CONTENIDO
- index.html: estructura de la app
- styles.css: diseño adaptable a iPhone
- app.js: funciones y almacenamiento local
- Informes: exportación a PDF e informe Excel con hojas separadas (requiere conexión para cargar el módulo XLSX la primera vez)
- manifest.webmanifest: configuración instalable
- sw.js: caché para funcionamiento sin conexión tras la primera carga
- icons/: iconos de la aplicación

PARA PUBLICAR Y USAR EN IPHONE
1. Subí el contenido completo de esta carpeta a un hosting HTTPS (por ejemplo, GitHub Pages, Netlify o Cloudflare Pages).
2. Abrí la URL HTTPS desde Safari en el iPhone.
3. Tocá Compartir > Añadir a pantalla de inicio > Añadir.
4. Abrí GYM TRACK desde el nuevo icono.

NOTAS
- Los datos se guardan en el almacenamiento local del navegador/dispositivo. No se sincronizan automáticamente entre dispositivos.
- Usá el botón superior para descargar una copia JSON de tus datos.
- En la pestaña Informes podés exportar el historial filtrado por fechas a PDF o Excel (.xlsx). El PDF se guarda desde la opción Imprimir/Compartir de Safari. Excel requiere conexión a internet para cargar la biblioteca de exportación.
- Para recuperar datos en otro dispositivo todavía hace falta implementar la función de importación.
- La PWA requiere HTTPS para instalarse correctamente y registrar el service worker.
- Las calorías de entrenamiento son aproximaciones basadas en MET, duración y peso corporal. No deben tratarse como mediciones exactas.
- La estimación de calorías diarias usa Mifflin-St Jeor y un factor de actividad seleccionado por el usuario. Es una orientación, no una prescripción médica.
