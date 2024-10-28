Descripción 
La grabadora de videos es una aplicación Android creada con Kotlin y Jetpack Compose, que ofrece a los usuarios la posibilidad de capturar videos a través de la cámara del dispositivo, guardarlos en la memoria interna, reproducirlos en la aplicación y administrar una lista de videos grabados con opciones para reproducir o eliminar cada uno de ellos.

Funcionalidades
Grabar Video: Utiliza la cámara del dispositivo para grabar videos. Los videos se guardan en una carpeta específica de la aplicación en la memoria interna.
Reproducir Último Video: Reproduce directamente el video más reciente grabado dentro de la aplicación.
Ver Videos Guardados: Muestra una lista de todos los videos grabados por la aplicación, permitiendo al usuario reproducir o eliminar cualquiera de ellos.
Eliminar Videos: Los usuarios pueden eliminar videos individualmente desde la lista de grabaciones.

Cómo Ejecutar el Proyecto
Prerrequisitos
Android Studio Flamingo | 2022.2.1 o superior: Descarga e instala Android Studio en tu computadora.
SDK de Android: Asegúrate de tener instalado el SDK de Android con un mínimo de API 21 y un máximo de API 33.
Dispositivo o Emulador Android: Un dispositivo físico con Android Lollipop (API 21) o superior, o un emulador configurado en Android Studio.

Pasos para Ejecutar
Clonar el Repositorio: Clona este repositorio en tu máquina local usando el siguiente comando:

bash
Copiar código
git clone https://github.com/Josue2704/GrabadoraAndroid.git
Abrir el Proyecto en Android Studio:

Abre Android Studio.
Selecciona "Open an Existing Project".
Navega hasta la carpeta donde clonaste el repositorio y selecciónala.
Sincronizar las Dependencias:

Android Studio debería comenzar a sincronizar las dependencias automáticamente.
Si no, ve a File > Sync Project with Gradle Files.
Ejecutar la Aplicación:

Conecta tu dispositivo Android o inicia un emulador.
Haz clic en el botón "Run" o ve a Run > Run 'app'.
Selecciona el dispositivo en el que deseas ejecutar la aplicación.

Requerimientos de la Aplicación
Permisos Necesarios
La aplicación requiere los siguientes permisos:

Cámara (android.permission.CAMERA): Para acceder y utilizar la cámara del dispositivo.
Grabación de Audio (android.permission.RECORD_AUDIO): Para grabar audio junto con el video.
Almacenamiento (No es necesario solicitar permisos adicionales debido al uso de almacenamiento interno específico de la aplicación).

Características de Hardware
La aplicación utiliza las siguientes características de hardware:

Cámara (android.hardware.camera): Requerido para grabar videos.
Micrófono (android.hardware.microphone): Requerido para capturar audio durante la grabación de videos.

Notas Adicionales
Gestión de Permisos: La aplicación maneja los permisos en tiempo de ejecución. Al iniciar la funcionalidad de grabación, se solicitarán los permisos necesarios si aún no han sido otorgados.
Espacio de Almacenamiento: Los videos se almacenan en la memoria interna del dispositivo dentro de una carpeta específica de la aplicación. Asegúrate de tener suficiente espacio disponible.
Eliminación de Videos: Puedes eliminar videos individualmente desde la lista de videos guardados deslizando el elemento o usando el botón de eliminar.

Contacto
Para más información o consultas, puedes contactarme:

Nombre: Josue Emanuel Hernandez Ortega
Correo Electrónico: josue3079@gmail.com
GitHub: https://github.com/Josue2704
