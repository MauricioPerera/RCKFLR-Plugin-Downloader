# RCKFLR Plugin Downloader

Este es un plugin de WordPress que agrega un enlace de descarga a cada plugin en la página de plugins de tu administrador de WordPress.

## Descripción

El plugin RCKFLR Plugin Downloader permite a los administradores de WordPress descargar cualquier plugin instalado en su sitio como un archivo zip. Esto puede ser útil para hacer copias de seguridad de plugins o para transferir plugins entre diferentes sitios de WordPress.

El código está escrito en PHP y realiza las siguientes acciones:

1. Agrega un filtro a los enlaces de acción de un plugin para que se pueda crear un enlace de "Descarga".
2. Crea una función que se activará cuando se haga clic en el enlace y comprobará si el usuario tiene suficientes permisos.
3. Recupera el nombre, la versión y la carpeta del plugin.
4. Crea un archivo zip del plugin.
5. Establece las cabeceras correctas y envía el archivo zip al usuario.

## Instalación

1. Descarga el archivo zip del plugin desde este repositorio.
2. Ve a tu administrador de WordPress y navega a Plugins > Añadir nuevo.
3. Haz clic en "Subir Plugin" y selecciona el archivo zip que acabas de descargar.
4. Haz clic en "Instalar ahora".
5. Una vez que el plugin se ha instalado, haz clic en "Activar Plugin".

## Uso

Una vez que el plugin está activado, verás un nuevo enlace de "Descarga" en la página de plugins de tu administrador de WordPress. Haz clic en este enlace para descargar el plugin correspondiente como un archivo zip.

## Soporte

Si tienes alguna pregunta o problema con el plugin, por favor abre un nuevo issue en este repositorio.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, haz un fork del repositorio y crea un nuevo pull request con tus cambios.

## Licencia

Este plugin está licenciado bajo la licencia GPL v2.0.

## Información del autor

* Autor: Mauricio Perera
* Enlace del autor: [LinkedIn](https://www.linkedin.com/in/mauricioperera/)
* Enlace de donación: [Buy me a coffee](https://www.buymeacoffee.com/rckflr)
