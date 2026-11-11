# Changelog

Todos los cambios importantes de OfflineTune.

## [2.4.0] - 2026-11-11

Incluye todo lo que se preparó después de la 2.2.4.

### Añadido
- **Videos:** modo Canción | Video en Buscar, pantalla de video (vertical, pantalla completa al girar y subtítulos), mini reproductor con su propia cola, imagen en imagen (PiP) y audio en segundo plano. SponsorBlock opcional y calidad máxima con datos móviles en Ajustes › Video.
- **Efecto cristal** en la barra de abajo y el mini reproductor (Ajustes › Apariencia).
- **Pantalla de Inicio:** seguir escuchando, accesos rápidos, tus listas y lo último que agregaste.
- **Favoritos:** orden propio arrastrando, buscador, selección de varias canciones y deshacer.
- **Listas:** Reproducir y Aleatorio, cambiar nombre, fijar, portada de mosaico, duración total y aviso de repetidas. Nuevas listas automáticas: Mix del día y Hace tiempo que no las escuchas.
- **Widget renovado:** controles sin abrir la app, progreso, color de la portada y tres tamaños.
- **Portadas de mayor calidad**, revisadas solas en segundo plano con Wi-Fi.
- **Tutorial** al abrir la app (con un paso para los videos) y accesos directos en el icono.
- Pega el enlace de una canción o lista en el buscador y se abre directo.
- Karaoke para leer de lejos, Modo Coche más grande y mejor diseño en tablets y pantallas chicas.

### Cambiado
- El instalador pasa de 18 MB a unos 4 MB.
- Calidad de descarga: quedan Baja y Normal (Alta daba lo mismo que Normal).

### Corregido
- Android 12 y anteriores: la búsqueda daba error y la app se cerraba al descargar.
- Cierre inesperado que podía ocurrir al abrir la app.
- Widget desactualizado o que abría el reproductor en lugar de obedecer.
- Listas y Favoritos: arrastrar movía otra canción, el corazón no respondía y la flecha de regresar no hacía nada; eliminar ahora pide confirmación.

## [2.2.4] - 2026-11-03

### Añadido
- **Normalización de volumen real** (sonoridad por canción, ITU-R BS.1770): baja las canciones fuertes y sube las bajas con limitador. Las canciones existentes se miden en segundo plano.
- **Recuperar respaldo:** botón «Descargar N canciones» para bajar los audios de las canciones importadas desde una copia de seguridad.
- **Idioma inglés** con selector Español / English en Ajustes › Apariencia.
- **Acerca de** con búsqueda de actualizaciones en GitHub, descarga e instalación del APK desde la app, y aviso automático de nueva versión (máx. 1 vez al día).

### Cambiado
- Descargas limitadas a **3 simultáneas**; el resto espera en cola.
- Notificaciones de descarga agrupadas: aviso con sonido al iniciar (con «Cancelar»), progreso silencioso «X de N» y aviso final con resumen y «Reintentar fallidas».
- Pantalla de Ajustes organizada en **secciones** desplegables.

### Corregido
- Los clips de menos de 1 minuto ya no se marcan por error como descarga incompleta.
- La normalización anterior solo subía +3 dB a todo por igual y a veces no se activaba.

## [2.2.3] - 2026-11-03

### Corregido
- **Fix:** Corrección de visibilidad del botón "Reproducir todo" y pestañas de categorías al ejecutar búsquedas desde el historial reciente.

### UI/UX
- Homologación del flujo de resultados de búsqueda entre entrada manual y recientes.

## [2.2.2] - 2026-10-23

### Añadido
- Botón **Compartir la app** en Ajustes.

## [2.2.1] - 2026-10-23

### Añadido
- Opción **Apoya OfflineTune** en Ajustes (Ko-fi).

### Cambiado
- Ajustes en el pie de la pantalla de Ajustes.
