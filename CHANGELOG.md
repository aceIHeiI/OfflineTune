# Changelog

Todos los cambios importantes de OfflineTune.

## [2.4.4] - 2026-11-18

### Añadido
- **Mini reproductor nuevo** con tres estilos a elegir en Ajustes › Apariencia: **A** tarjeta flotante, **B** barra plana y **C** color de la portada (degradado, resplandor, progreso y play con el color del disco, y un ecualizador). El C es el predeterminado y luce muchísimo en negro AMOLED. Ahora solo se ve un mini reproductor a la vez.
- **OfflineTune Car + Velora Drive:** el siguiente y el anterior del estéreo siguen la cola del celular, al terminar un video pasa solo al siguiente, y si cambias de canción en el celular el video nuevo llega al coche sin volver a pulsar "Ver en el coche".
- En **Buscar › Videos**: botones **Reproducir todo** y **Aleatorio**. Al mandar un resultado al coche, el siguiente, el anterior y el fin del video siguen la lista de la búsqueda (antes saltaba a otro video).
- El mini reproductor del coche abre una hoja con el video que está en el coche (antes abría la última canción del celular).
- La **X** del mini reproductor del celular también cierra el video en Velora, y desde el celular puedes pausar o reanudar el video del coche.
- Al activar la conexión en Xiaomi, Samsung y otras marcas, un aviso explica cómo permitir la ejecución en segundo plano para que no se corte con el celular bloqueado.

### Corregido
- La posición del video en el coche se refleja en el celular cada segundo (antes cada 5), también en modo Canción.
- La notificación "Seguir viendo en el celular" ya no se queda pegada: se quita al reconectar el coche, al abrir la app o a los 10 minutos.
- En pantallas muy angostas el mini reproductor deja más espacio al título.

✅ **Probado en un celular y un estéreo Android reales.** Si encuentras algo raro, cuéntame en un [Issue](https://github.com/aceIHeiI/OfflineTune/issues).

## [2.4.3] - 2026-11-17

### Corregido
- **Video en canciones importadas:** las canciones agregadas desde un archivo (sin descargarlas desde YouTube) ya no muestran la opción **Video** con el error "Revisa la conexión". Ahora esa opción se oculta y aparece el aviso "Esta canción no tiene video de YouTube". Las canciones descargadas desde Buscar siguen mostrando su video.

## [2.4.2] - 2026-11-15

### Añadido
- **OfflineTune Car** se publica junto a la app normal: edición para conectar el celular con el estéreo del coche (Velora Drive).

### Cambiado
- Pequeños ajustes internos en la biblioteca.

## [2.4.1] - 2026-11-15

### Corregido
- Las portadas de las canciones descargadas ya no aparecen en la Galería ni en Fotos: ahora se guardan en una carpeta oculta (`.covers`) dentro de la carpeta de música. Las que ya tenías se mueven solas al abrir la app.

## [2.4.0] - 2026-11-11

### Añadido
- **Video:** modo Canción | Video en Buscar, pantalla de video propia (vertical, pantalla completa al girar y subtítulos), mini reproductor con su propia cola, imagen en imagen (PiP) y audio en segundo plano con su notificación.
- **SponsorBlock** opcional para saltar los patrocinios dentro del video, también intros y outros.
- Ajustes › Video: calidad máxima con datos móviles y permiso para seguir funcionando con el celular bloqueado.

## [2.3.0] - 2026-11-04

### Añadido
- **App mucho más ligera:** el instalador pasa de 18 MB a unos 4 MB, con las mismas funciones.
- **Widget renovado:** botones anterior, reproducir, siguiente y favorito que funcionan sin abrir la app; barra de progreso y tiempos; siguiente canción; fondo con el color de la portada y tres tamaños que se adaptan solos.
- El botón de reproducir del widget retoma lo último que sonaba, aunque la app esté cerrada.
- Botón para agregar el widget desde Ajustes › Apariencia, en los equipos que lo permiten.
- **Pantalla de Inicio:** seguir escuchando, accesos rápidos, tus listas y lo último que descargaste. Ajustes se abre con el engrane.
- **Favoritos:** tu propio orden arrastrando la agarradera, buscador, selección de varias canciones, agregar a listas y deshacer.
- **Listas:** Reproducir y Aleatorio, agregar canciones desde dentro, cambiar nombre, fijar, portada de mosaico, número de canciones y duración total; deshacer al quitar una canción y aviso de canciones repetidas.
- Nuevas listas automáticas: Mix del día y Hace tiempo que no las escuchas.
- Agarradera a la derecha en listas, Favoritos y cola, y nombre que se desplaza en la canción que está sonando.
- **Tutorial** al abrir la app, que se puede repetir desde Ajustes.
- **Accesos directos** al mantener presionado el icono de la app.
- **Enlaces de YouTube en el buscador:** pega el enlace de una canción, una lista o un mix y se abre para reproducirlo o descargarlo (hasta 100 canciones por lista).
- **Tablets y otras medidas:** el reproductor siempre deja ver sus controles, las listas no se estiran en pantallas anchas, la Biblioteca en horizontal muestra portadas y más columnas en tablet, y las pantallas chicas muestran más del título. Si la pantalla tiene la medida de un autoestéreo, la app pregunta una vez cómo mostrarse.
- **Karaoke para leer de lejos:** muestra toda la letra en grande y se puede deslizar, con o sin sincronización; si está sincronizada, sigue la canción.
- **Coche:** Modo Coche más grande con letra y diseño apaisado, letras más grandes en pantallas de radio y opción Seguir sonando al encender.

### Corregido
- Los botones del widget abrían el reproductor en lugar de solo obedecer.
- El widget se quedaba desactualizado si la música seguía con la app cerrada.
- Karaoke: el gesto de regresar no funcionaba, y la flecha y la X quedaban encimadas con la barra de estado.
- Listas: al arrastrar una canción podía moverse otra, el corazón no respondía y las canciones nuevas no siempre quedaban al final.
- Favoritos: la flecha de regresar no hacía nada, y eliminar borraba el archivo sin pedir confirmación.
- Portadas: ya no aparece un error si la revisión empieza con la app en segundo plano.

## [2.2.9] - 2026-11-04

### Corregido
- **Android 12 y anteriores:** la búsqueda daba error y la app se cerraba al descargar. Ya funcionan también en autoestéreos y equipos con esas versiones.
- Si falta una función en el sistema, la app muestra un aviso en lugar de cerrarse.
- Recuperar respaldo: el botón para descargar las canciones podía no aparecer con respaldos pequeños.

## [2.2.8] - 2026-11-04

### Corregido
- La revisión de portadas sigue en segundo plano y con el teléfono bloqueado, con una notificación que muestra el avance y permite detenerla. Si se corta el Wi-Fi, continúa sola al volver.

## [2.2.7] - 2026-11-04

### Añadido
- **Revisar portadas:** en Ajustes › Mantenimiento de biblioteca se ve el avance y si está en pausa, con un botón para iniciar la revisión.

### Corregido
- La revisión de portadas reintenta si falla la conexión o el catálogo, y continúa sola al volver el Wi-Fi.

## [2.2.6] - 2026-11-04

### Añadido
- **Portadas de mayor calidad:** se usa la portada oficial del álbum o sencillo cuando coinciden artista, título y duración; si no, la imagen de YouTube más grande disponible, sin franjas negras.
- Las canciones ya descargadas se revisan solas en segundo plano, solo con Wi-Fi. Las portadas elegidas a mano no se reemplazan.
- Las canciones sin álbum lo reciben si la búsqueda encuentra uno con certeza.
- Al importar se reconocen las portadas que están junto al audio y las que van dentro del archivo.

### Cambiado
- **Portadas con nombre legible:** cada imagen se llama igual que su canción, también las que ya tenías.

### Corregido
- Portadas vacías o dañadas: se vuelven a descargar.

## [2.2.5] - 2026-11-04

### Cambiado
- **Calidad de descarga simplificada:** quedan Baja y Normal. «Alta» se quitó porque YouTube entregaba lo mismo que Normal; quien la tenía elegida pasa a Normal.

### Corregido
- Cierre inesperado que podía ocurrir al abrir la app.

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
