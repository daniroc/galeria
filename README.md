# Galería de imágenes
Queremos crear una galería de imágenes que nos permita añadir, editar y eliminar imágenes.

## Preparación

- Después de analizar el proyecto y hacer varias pruebas con distintas alternativas he decidido que JavaScript y PHP se adaptan bien al objetivo del proyecto.
- He hecho un esquema de la web en el que hay una página inicial con login, registro y la opción de recuperar contraseña.
- Una vez que haces login se accede a una página donde aparecen las opciones de logout y añadir imágenes a la galería. 
- Debajo hay un buscador y al hacer una búsqueda se filtran las imágenes.
- Por último voy a crear filas de imágenes con vistas en miniatura y que por encima haya botones con las distintas opciones.
- Los archivos que contienen HTML y los de configuración irán en la raíz del proyecto y los que sólo contengan JavaScript, CSS, imágenes y PHP irán en carpetas.


## Requisitos

Tener un servidor web con PHP y MariaDB. En mi caso voy a utilizar la versión 8.1 de PHP y la versión 10.3 de MariaDB.

## Pasos a seguir

- Hacer la estructura general de las páginas del proyecto
- Maquetar con HTML los elementos necesarios para generar los formularios y los bloques con las imágenes introduciendo datos estáticos
- Posicionar correctamente los elementos con CSS para estructurar bien las páginas
- Generar el contenido de los bloques de imágenes obteniendo los datos de un JSON de ejemplo
- Obtener el listado de imágenes de la base de datos de Firebase
- Darle funcionalidad a los formularios para añadir, editar o eliminar imágenes de la base de datos
- Añadir funcionalidades extra que mejoren la experiencia de usuario de la web, el posicionamiento y que optimicen el proceso de almacenamiento de las imágenes
