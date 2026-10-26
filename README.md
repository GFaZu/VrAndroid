# Cámara VR (Android)

App que muestra la cámara en pantalla dividida para gafas tipo Cardboard.

## Cómo obtener el APK
1. Crea un repositorio nuevo en GitHub y sube TODO el contenido de esta carpeta
   (incluida la carpeta oculta `.github`).
2. Ve a la pestaña **Actions**. El workflow "Build APK" se ejecuta solo (tarda 3-5 min).
3. Abre la ejecución terminada y descarga **CamaraVR-apk** (viene en un .zip con app-debug.apk).
4. Instala el APK en el celular (acepta "instalar apps de orígenes desconocidos").

## Nota
La versión con manos carga el detector (MediaPipe Hands) desde internet la primera vez,
así que el celular necesita conexión al abrir la app.
