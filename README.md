# Sync_Lyx

**Version estable actual: Sync_Lyx v1.2.0** · [Descargar v1.2.0](../../releases/latest)

Novedades destacadas en v1.2.0: extraccion de APKs (saca las aplicaciones instaladas de un emulador o de un telefono, con todos sus splits, y las guarda en una carpeta por aplicacion), ajustes de Windows y aligerado del emulador en tres niveles reversibles, limite de FPS, bloqueo de anuncios de now.gg, medidores de procesador y memoria en vivo, e interfaz rediseniada por completo.

Instala y extrae APKs en emuladores Android, y deja Windows listo para que corran mejor

[Discord](https://discord.gg/wVPtCwZ58z) · [YouTube](https://www.youtube.com/@Nks_v1) · [Ko-fi](https://ko-fi.com/nks_array) · [Descargar](../../releases/latest)

## Que es Sync_Lyx?

Sync_Lyx es una herramienta para Windows que instala y extrae APKs en emuladores Android y ajusta el equipo para que los juegos corran mejor, sin usar comandos ni instalar ADB por separado.

Pensada para quien juega Free Fire en emulador.

## Por que Sync_Lyx?

**Sin comandos ni configuracion.** Todo lo que normalmente harias en una terminal (conectar por ADB, instalar paquetes divididos, extraer un APK ya instalado) se hace desde la interfaz.

**Todo listo para usar.** No necesitas instalar .NET, ADB ni platform-tools. Todo viene incluido en cada version.

**Reversible.** Los ajustes de Windows y del emulador guardan su valor original y se revierten desde la misma aplicacion. Ningun paquete del emulador se desinstala: solo se desactiva.

**Pasa juegos entre dispositivos.** Extrae Free Fire del telefono e instalalo en el emulador, o al reves, sin volver a descargarlo.

## Descarga

| Formato | Enlace |
|---|---|
| Instalador, Windows 10/11 x64 (recomendado) | [SyncLyx_Setup_v1.2.0.exe](https://github.com/sudoNks/SyncLyx/releases/download/v1.2.0/SyncLyx_Setup_v1.2.0.exe) |
| Portable, Windows 10/11 x64 | [SyncLyx_Portable_v1.2.0.zip](https://github.com/sudoNks/SyncLyx/releases/download/v1.2.0/SyncLyx_Portable_v1.2.0.zip) |

Todas las versiones: [Releases](../../releases)

La version portable no necesita instalacion: descomprime la carpeta y abre SyncLyx.exe.

## Requisitos

**PC:** Windows 10 o Windows 11 de 64 bits, con permisos de administrador. ADB incluido, no requiere instalacion adicional.

**Emulador:** BlueStacks o MSI App Player, con el Android Debug Bridge activado en sus ajustes. Solo hace falta si vas a instalar o extraer aplicaciones.

## La primera vez que lo abras

Windows va a mostrar un aviso de SmartScreen porque el instalador no esta firmado digitalmente. Pulsa **Mas informacion** y luego **Ejecutar de todas formas**.

## Que incluye

**Instalacion de APKs.** Detecta la arquitectura de la carpeta, busca el emulador y hace la instalacion completa, incluidos los paquetes divididos en varios APK.

**Extraccion de aplicaciones.** Lee los splits reales del dispositivo y los guarda en una carpeta con el nombre del paquete, con progreso y velocidad en vivo.

**Ajustes de Windows.** Tres niveles: esenciales para jugar, privacidad y ruido del sistema, y rendimiento visual. Todos reversibles.

**Aligerado del emulador.** Tres niveles de paquetes que el emulador no necesita, mas limite de FPS y bloqueo de anuncios de now.gg.

**Planes de energia.** Aplica perfiles, importa los incluidos y crea el plan Ultimate Performance de Windows.

**Limpieza.** Archivos temporales, papelera y reinicio de la cache de shaders.

## Cosas que conviene saber

La aplicacion pide permisos de administrador porque modifica el registro de Windows, los planes de energia y el archivo hosts.

El nivel 3 del aligerado de emulador puede romper Free Fire en algunas versiones. Esta marcado con su advertencia dentro de la aplicacion.

Chrome nunca se desactiva, porque el inicio de sesion con Facebook depende de su WebView.

## Historial de versiones

| Version | Descripcion | Descargar |
|---|---|---|
| v1.2.0 | Extraccion de APKs, ajustes de Windows y del emulador en tres niveles, medidores en vivo e interfaz rediseniada | [Descargar](../../releases/tag/v1.2.0) |
| v1.0.0 | Primera version estable: instalacion de APKs, limpieza, shaders y planes de energia | No publicada en GitHub |

## Creditos

Los ajustes de Windows provienen del catalogo de [winutil](https://github.com/ChrisTitusTech/winutil), de Chris Titus Tech, licencia MIT. Se selecciono un subconjunto, se reescribieron los textos en espaniol y se agruparon en niveles.

Android Debug Bridge es parte de las Android SDK Platform Tools de Google, licencia Apache 2.0. El aviso correspondiente viaja dentro de la aplicacion.

Sync_Lyx es un proyecto independiente creado por [@sudoNks](https://github.com/sudoNks).

## Licencia

Sync_Lyx - Licencia de uso

Copyright (c) 2026 Dario (@nks_array)

Sync_Lyx es gratuito. Puedes usarlo y compartirlo libremente, siempre que se distribuya el instalador original, completo y sin modificar. No esta permitido modificarlo, descompilarlo, venderlo ni presentarlo como obra propia.

El codigo fuente es propietario y no forma parte de esta distribucion.

Se entrega sin garantia de ningun tipo. Sync_Lyx modifica ajustes del sistema; todos quedan registrados con su valor original y pueden revertirse desde la aplicacion, pero el autor no se hace responsable de danios derivados de su uso.

winutil y Android Debug Bridge conservan sus respectivas licencias y no forman parte de esta.

Texto completo: [LICENSE](LICENSE)
