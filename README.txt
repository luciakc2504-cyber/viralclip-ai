VIRALCLIP AI — PRIMERA VERSIÓN (PWA)

QUÉ INCLUYE
- Interfaz adaptable a móvil y escritorio.
- Campo para enlace de YouTube y selección de archivo.
- Validación básica de enlaces.
- Selección de cantidad y formato de clips.
- Historial local básico del navegador.
- Planes ilustrativos.
- Manifiesto PWA y service worker para instalación desde navegador compatible.

IMPORTANTE
Esta es una primera versión de interfaz/prototipo. Todavía NO:
- descarga videos de YouTube;
- genera clips reales;
- ejecuta análisis de IA;
- crea cuentas seguras;
- procesa pagos ni suscripciones.

Para producción se debe conectar un backend seguro, almacenamiento, motor de video (por ejemplo FFmpeg), transcripción/IA, autenticación y proveedor de pagos. No se deben poner claves secretas en app.js ni en archivos públicos.
Procesar videos de YouTube requiere respetar términos, permisos y derechos de autor. Permite solamente material propio o autorizado.

CÓMO USARLO DESDE ANDROID
1. Descarga y descomprime el ZIP en tu teléfono.
2. Para probarlo localmente, abre index.html con un navegador. Algunas funciones PWA requieren HTTPS.
3. Para instalarlo como app, publica la carpeta en un hosting HTTPS (por ejemplo GitHub Pages o Netlify) y abre la URL en Chrome Android.
4. En Chrome, menú ⋮ > Instalar aplicación o Añadir a pantalla principal (la opción depende del navegador).

RECOMENDACIÓN
Usa GitHub desde Chrome Android:
- Entra a github.com y crea una cuenta si no tienes.
- Crea un repositorio público llamado viralclip-ai.
- Sube los archivos de esta carpeta a la raíz del repositorio.
- En Settings > Pages, configura Deploy from a branch, selecciona main y /root.
- Espera a que GitHub Pages publique la URL HTTPS.
Los nombres de los menús pueden variar según la interfaz móvil.

SIGUIENTE ETAPA
Conectar Supabase Auth/Database, almacenamiento privado, cola de procesamiento, FFmpeg y proveedor de IA. Después, integrar pagos recurrentes y paquetes con verificación de webhook en servidor.
