# Sync_Lyx

Herramienta para Windows que instala y extrae APKs en emuladores Android, y deja el equipo listo para que corran mejor.

Pensada para quien juega Free Fire en emulador y no quiere pelearse con ADB, variables de entorno ni tutoriales sueltos.

## Descargar

La última versión está en la sección [Releases](../../releases/latest).

Se descarga un solo instalador. No hace falta instalar nada más.

## Qué hace

**Instalar APKs**

Selecciona la carpeta con los archivos y Sync_Lyx detecta la arquitectura, busca el emulador y hace la instalación completa, incluidos los paquetes divididos en varios APK.

**Extraer aplicaciones**

Saca los APK ya instalados de un emulador o de un teléfono, con todos sus splits reales, para instalarlos en otro lado. Útil para pasar un juego del teléfono al emulador sin volver a descargarlo.

**Optimizar Windows**

Ajustes de rendimiento y privacidad agrupados en tres niveles. Todos guardan el valor original, así que se revierten desde la misma aplicación.

**Aligerar el emulador**

Apaga los paquetes de Android que el emulador no necesita, sube el límite de FPS y bloquea los anuncios de now.gg. Nada se desinstala: todo queda desactivado y se puede reactivar.

**Planes de energía**

Aplica perfiles de energía, importa los perfiles incluidos y crea el plan Ultimate Performance de Windows.

**Limpieza**

Analiza y borra archivos temporales, vacía la papelera y reinicia la caché de shaders de la tarjeta gráfica.

## Requisitos

- Windows 10 o Windows 11 de 64 bits
- Permisos de administrador
- Un emulador Android compatible si vas a instalar o extraer aplicaciones

No necesitas instalar .NET, ADB ni platform-tools. Todo va incluido.

## Emuladores compatibles

- BlueStacks
- MSI App Player

## La primera vez que lo abras

Windows va a mostrar un aviso azul de SmartScreen porque el instalador no está firmado digitalmente. Firmar un programa tiene un costo anual que este proyecto no cubre por ahora.

Para continuar, pulsa **Más información** y luego **Ejecutar de todas formas**.

## Cosas que conviene saber

- La aplicación pide permisos de administrador porque modifica el registro de Windows y los planes de energía.
- Todos los ajustes de Windows guardan su valor original y se revierten desde la aplicación.
- El nivel 3 del aligerado de emulador puede romper Free Fire en algunas versiones. Está marcado con su advertencia.
- Chrome nunca se desactiva, porque el inicio de sesión con Facebook depende de su WebView.

## Créditos

Los ajustes de Windows provienen del catálogo de [winutil](https://github.com/ChrisTitusTech/winutil), de Chris Titus Tech, publicado bajo licencia MIT. Se seleccionó un subconjunto, se reescribieron los textos en español y se agruparon en niveles.

La aplicación incluye Android Debug Bridge, parte de las Android SDK Platform Tools de Google, bajo licencia Apache 2.0. El aviso correspondiente viaja dentro de la aplicación.

## Comunidad

- YouTube: [@Nks_v1](https://www.youtube.com/@Nks_v1)
- TikTok: [@nks_array](https://www.tiktok.com/@nks_array)
- Ko-fi: [nks_array](https://ko-fi.com/nks_array)

## Licencia

Consulta el archivo [LICENSE](LICENSE).

Este repositorio distribuye la aplicación compilada. El código fuente no es público.
