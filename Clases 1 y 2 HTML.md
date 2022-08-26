# HTML intro
[//]: <> (por comodidad voy a usar un solo archivo MarkDown para varias clases sino todas.)
## Instalación de plugins video N.º 2 Y su utilización

Nada demasiado importante, ver luego como habilitar live server para que actualice automáticamente, minuto 14.

* Creo la carpeta 01-introducción
* El profesor recomienda usar chrome por las herramientas para devs. se pueden inspeccionar elementos e incluso hacer 
* cambios.

Por ahora solo explicación de etiquetas sencillas y comentarios.

### Instale better comments funciona dentro del comentario por defecto sino NO
![img_2.png](img_2.png)
![](C:/Users/gustavo/AppData/Local/Temp/better-comments.png) ![img_4.png](img_4.png)

Habiendo configurado *prettier* como estilo de **formato de documento** con la combinación `shift + alt + f` mejora 
el formato de manera automática. **No sé, por qué hubo una actualización y pensé que se había roto la app**

Descargué un diccionario inglés y uno español abarca el espacio de trabajo y la sección de carpetas también, 
con crt +. me ofrece las correcciones.

#### Path Intellisense: Me resolvió el tema de insertar imágenes de otra carpeta en VsCode
Para insertar multimedia pongo "/" y me abre las rutas gracias al plugin nuevo 

## Clase N°1 
### Etiquetas Habituales

![img.png](img.png)

Cuando utilizo VsCode me ofrece vincular con el archivo existente de manera interna.

***Automáticamente, intelJ que es donde me es más cómodo utilizar Mark Down por el uso de imágenes me crea su carpeta y 
decido agregarla a git en vez de usar git ignore***

* Cada elemento dentro de las etiquetas capaz de modificarla se llama atributo.

## Clase N°2 
### Formularios
![img_1.png](img_1.png)

En este caso con clic derecho abro la página con live server la extension para que actualice automáticamente.
Creamos formulario muy básico con sus etiquetas ingresamos los datos con input, luego creamos otra html para alojar 
los datos.

Hay 2 *métodos* para esto uno es `GET` y el otro `POST` el primero get se utiliza para html, el segundo se utiliza para 
interactuar con servidores y BB DD.

En nuestro ejemplo utilizamos el método `GET` y para que se pueda acceder en la etiqueta **input** es necesario establecer 
un nombre ``name`` también `id` y si quiero que sea un campo obligatorio le agrego el atributo `required`
#### Cargo los datos
![img_6.png](img_6.png) 
#### Quedan almacenados y se ven el la barra de dirección
![img_5.png](img_5.png)
#### Con este ejemplo muestro que si solo creo la etiqueta y campo, pero no agrego los atributos este existe pero no se guarda
![img_7.png](img_7.png)     ![img_8.png](img_8.png)
![img_9.png](img_9.png)

Ahora si con atributos para comentarios:

![img_11.png](img_11.png)
![img_10.png](img_10.png)

Para saber acerca de los atributos dentro de las etiquetas puedo consultar la documentación 
en: https://www.w3schools.com/tags/ref_attributes.asp.

### Botones
Dos de los botones más utilizados son, según su acción `submit` y `reset`. 

En sus respectivos inputs a través de sus atributos establezco el tipo ``type`` en nombre texto y en contraseña password.
Otros ejemplos son número, e-mail, fecha.. sencillamente, me va a requerir esos tipos de datos.
![img_12.png](img_12.png)

![img_13.png](img_13.png)

### Tablas
Al menos en la 1.er clase no hay demasiado para explicar, las etiquetas son sencillas y la tabla si no le pasamos formato 
va tomando forma sola. 

etiquetas de esta clase: ``<table> / <th> / <td>``
 Ejercicio n.º 2:
![img_14.png](img_14.png) 
![img_15.png](img_15.png)
![img_16.png](img_16.png)
Lo interesante del resultado es que el **live server** abrio la carpeta superior a donde está creado este trabajo.

![img_17.png](img_17.png) 

Sin live server, o sea "open in default browser" arrojó este resultado.

**En github el ejercicio siguiente.**

## Clase nº3 
### Multimedia

#### Imágenes
*He descargado una imagen un video y un audio para explicar las etiquetas.* https://www.w3schools.com/html/html_images.asp

The `<img>` tag has two required attributes:

``src`` - Specifies the path to the image
``alt`` - Specifies an alternate text for the image

``<img src="url" alt="alternatetext">``

Para usar imágenes de internet puedo copiar la dirección de imagen.

#### Videos
Los navegadores soportan varios formatos, se puede manipular altura y ancho como enm las imágenes, también utilizar 
autoplay aunque no es muy recomendado. Son útiles los atributos, ``mute`` y ``loop``.

#### Audio
Muy similar a video en este caso utilizo la sintaxis del profesor a diferencia de video que use la sugerida por vsCode.

