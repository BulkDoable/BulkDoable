CAMPUS DEMO - PWA PARA IPHONE
================================
1. Subir todos los archivos de esta carpeta a un hosting HTTPS (GitHub Pages, Netlify o similar). Mantener los archivos juntos.
2. Abrir la URL publicada desde Safari en el iPhone 16e.
3. En Safari, pulsar Compartir > Añadir a pantalla de inicio > Añadir (la ubicación exacta del menú puede variar con iOS).
4. Abrir Campus Demo desde el icono de inicio. Pulsar «Editar» para cambiar los campos y seleccionar una foto.
5. El perfil se guarda en localStorage y la fotografía comprimida en IndexedDB. La aplicación guarda recursos en caché para funcionar offline tras la primera carga completa.
6. El reloj usa la fecha y hora del iPhone, sin verificación externa. No constituye prueba de hora confiable.
7. Este prototipo no es una identificación oficial. Mantener el rótulo visible «PROTOTIPO · NO VÁLIDO COMO IDENTIFICACIÓN».
NOTA: abrir index.html directamente desde Archivos no permite instalar correctamente el service worker. Para instalar la PWA es necesario servirla desde HTTPS (o localhost para pruebas).
