# MarkDown del proyecto Symfony de recuperación.

## Resumen
He creado este proyecto siguiendo las instrucciones indicadas en la tarea correspondiente a este ejercicio. Es una página web que funciona como un gestor de artículos o noticias. 

Para hacer el proyecto he usado _Symfony_ y _Bootstrap 5_. Tiene las funciones básicas de un CRUD, podemos crear artículos, eliminar artículos, editar artículos, buscar un artículo en concreto y buscar por una categoría en concreto.

## Cómo usar el proyecto
Entramos en el proyecto desde el Visual Studio Code(o similar) abrimos un terminal y ejecutamos el comando **symfony server:start**

Nada más abrir la aplicación nos ubicaremos en el home, una vez allí veremos una página dónde tendremos una columna con las diferentes categorías disponibles de artículos, pulsando las diferentes categorías se nos mostrarán los artículos pertenecientes exclusivamente a esa categoría. Al lado de la columna se nos mostrará una zona con una vista previa de los artículos seleccionados, en esa zona cada artículo tendrá un botón llamado Ver que nos llevará a otra página con la información completa del artículo. 

Dentro de la página del artículo, tendremos a mayores de la información, un botón para editar la información del artículo y un botón para borrarlo en caso de querer hacerlo.

Además en todas las páginas se nos mostrará un botón que nos permitirá crear nuevos artículos.

## Requisitos del entorno de desarrollo

Para el desarrollo necesitaremos tener un programa de editor de código del estilo del  Visual Studio Code y tener instalado lo necesario para usar correctamente el framework de _Symfony_.

## Guía de instalación y funcionamiento

Necesitaremos instalar Symfony, para ello nos dirigiremos a esta web -> https://symfony.es/pagina/descargar/

Instalamos el framework y abrimos el código del programa en Visual Studio Code. Una vez abierto, abrimos la consola de comandos del IDE y escribimos:

~~~

symfony server:start

~~~

Con este comando, ejecutaremos la aplicación en un servidor local.

## Tecnologías utilizadas


|Tecnología|Versión|
|---------|---------|
|**Symfony**  |    6.0.4    |
|**Bootstrap**|    5    |
| **HTML**    |    5   |

## Autor o autores

**Andrés Varela Couceiro**

## Licencia

## Cómo contribuir al proyecto

En un futuro añadiré un enlace a mi github para que podáis echarle un vistazo y hacer modificaciones.