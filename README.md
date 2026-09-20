AutoPower Spectrum Analyzer v4.7 - instalación de la PWA en GitHub Pages

1. Abrí el repositorio javierhstella/AutoPower en la rama que sirve GitHub Pages.
2. Subí LOS SEIS archivos de esta carpeta, todos juntos y en la raíz del repositorio:
   index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, icon-maskable-512.png
   Es importante que se llame exactamente index.html, con i minúscula.
3. Esperá que el despliegue de GitHub Pages termine.
4. Abrí https://javierhstella.github.io/AutoPower/?v=47 en Chrome de Android.
5. Menú de Chrome (tres puntos) > Instalar aplicación / Agregar a pantalla principal.
6. ABRÍ EL ÍCONO INSTALADO desde el inicio Android: eso aplica display: fullscreen.

Si Chrome sólo crea un acceso directo y sigue mostrando la barra, tocá el
botón ⛶ de la cabecera del Spectrum Analyzer: solicita la pantalla completa.
Chrome/Android decide si deja visibles barras del sistema o muestra permisos.

El botón CONTROL ESP sigue abriendo http://192.168.1.13/control.
Por seguridad, el micrófono sigue requiriendo pulsar ACTIVAR MICRÓFONO.
El analizador utiliza exclusivamente el micrófono del celular.

No hay cambios de firmware ESP8266 en esta versión.
