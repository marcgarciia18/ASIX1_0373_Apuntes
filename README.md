# ASIX1_0373_Apuntes
Apuntes de Lenguaje de Marcas Marc Garcia Bardales

# ASIX1_AprendizajeMarkdown
## Segundo nivel de encabezado
### Tercer nivel de encabezado
#### Cuarto nivel de encabezado
##### Quinto nivel de encabezado
###### Sexto nivel de encabezado

Estos son mis apuntes del __"0373"__ del ciclo de ASIX del curso **24/25**

Las etiquetas en **_markdown_** y HTML pueden anidarse.

1. Primer punto de la lista
    1. Primer elemento de la sublista 1
    2. Segundo elemento de la sublista 1
2. Segundo punto de la lista
    * Primer elemento de la sublista 2
    * Segundo elemento de la sublista 2
3. Tercer punto de la lista 

* Primer punto de la lista desordenada
- Segundo punto de la lista desordenada
+ Tercer punto de la lista desordenada


Lorem Ipsum es simplemente el texto de relleno de las imprentas y archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de las industrias desde el año 1500, cuando un impresor (N. del T. persona que se dedica a la imprenta) desconocido usó una galería de textos y los mezcló de tal manera que logró hacer un libro de textos especimen. No sólo sobrevivió 500 años, sino que tambien ingresó como texto de relleno en documentos electrónicos, quedando esencialmente igual al original. Fue popularizado en los 60s con la creación de las hojas "Letraset", las cuales contenian pasajes de Lorem Ipsum, y más recientemente con software de autoedición, como por ejemplo Aldus PageMaker, el cual incluye versiones de Lorem Ipsum.

**Como mostrar código en un repositorio**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>

```
## Como poner un link
[textoclick](URL "TituloOpcional")

[Pagina web de Jesuites Bellvitge](https://www.fje.edu/ca/jesuites-bellvitge "TituloOpcional")

## Como poner una imagen

![JcReyes](https://github.com/marcgarciia18/ASIX1_AprendizajeMarkdown/blob/main/Imagenes/JC.jpg "ReyDeEspaña")


## Como añadir tablas

|Titulo 1 | Titulo 2 | Titulo 3 |
|:----------:|:---------------:|:----------:|
|SMX2|Curso 23-24 |25|
|**ASIX1**|Curso 24-25|33|
|DAW2|Curso 24-25|29|

___

# Git
Git es un sistema de control de versiones que permite a los desarrolladores rastrear cambios en el código, trabajar en diferentes versiones simultáneamente y colaborar de manera efectiva.

## Comandos basicos de git
+ git clone -> sirve para clonar nuestro repositorio en loca
+ git init -> reinicia el repositorio
+ git branch -> crea diferentes ramas de desarrollo que pueden converger en el mismo repositorio
+ git add -> añade contenido del directorio de trabajo al área de ensayo
+ git commit -m "Comentario del comit" -> sirve para realizar commits con un mensaje
+ git push origin main -> sincroniza el repositorio local con el que esta en red
+ git pull -> si modificamos el repositorio online sirve para sincronizarlo con el local

___

# Github
GitHub es una plataforma de desarrollo colaborativo que utiliza el sistema de control de versiones Git. Permite a los desarrolladores almacenar, compartir y trabajar en proyectos de código fuente de manera conjunta

## Como crear un repositorio

1. Deberemos darle a **_create new repositor_**

![Repositorio](https://github.com/marcgarciia18/ASIX1_0373_Apuntes/blob/main/img/crear_repo.png "Crear nuevo repositorio")

2. Configuraremos el repositorio con cosas como pueden ser:
    + Nombre del repositorio
    + Descripcion adicional para este
    + Decidir si hacerlo publico o no
    + Inicializar el repositorio
    + Añadir un README al repositorio
![Repositorio](https://github.com/marcgarciia18/ASIX1_0373_Apuntes/blob/main/img/nuevo_repo.png "Configurar nuevo repositorio")


## Como clonar un repositorio
Para clonar un repositorio en github deberemos seguir los siguientes pasos:
1. Deberemos obtener nuestra _URL_ del repositorio que queremos clonar, para ello debe estar creado previamente y una vez lo tengamos deberemos acceder al **_boton verde "CODE"_** y en el desplegable veremos la url en _HTTPSS_, copiaremos esta para luego

![Repositorio](https://github.com/marcgarciia18/ASIX1_0373_Apuntes/blob/main/img/url_clonar.png "URL para clonar repositorio")

2. Una vez con la _URL_ deberemos ir a nuestro **_CMD_** para poder clonarlo, una vez dentro de este deberemos buscar la carpeta donde tenemos nuestro repositorio

![Repositorio](https://github.com/marcgarciia18/ASIX1_0373_Apuntes/blob/main/img/cmd_repo.png "Carpeta donde esta repositorio")

3. Cuando estemos dentro de la carpeta deberemos utilizar el siguiente comando -> **_git clone "pegar url"_** 


![Repositorio](https://github.com/marcgarciia18/ASIX1_0373_Apuntes/blob/main/img/git_clone.png "Comando git clone")

4. Finalmente ya tendremos clonado el repositorio que se encuentra en red en local.

![Repositorio](https://github.com/marcgarciia18/ASIX1_0373_Apuntes/blob/main/img/repo_clonado.png "Repositorio clonado en local")

___

# HTML

## Introduccion a HTML

### ¿Qué es HTML?

HTML (HyperText Markup Language) es el lenguaje estándar para crear páginas web. Imagina que es como un conjunto de bloques de construcción que te permiten estructurar y dar formato al contenido de una página web. Estos bloques se llaman "etiquetas".

### ¿Para que sirve HTML?

+ **Organizar el contenido:** Define la estructura de una página, como encabezados, párrafos, listas, tablas, etc.
+ **Incluir multimedia:** Permite insertar imágenes, videos, audio y otros elementos multimedia en una página.
+ **Crear enlaces:** Crea vínculos a otras páginas web o a diferentes secciones de la misma página.
++ **Dar formato:** Aunque de forma básica, puedes aplicar negrita, cursiva y otros estilos simples al texto.

## Estructura basica de HTML

+ **<!DOCTYPE html>:** Declara el tipo de documento.
+ **<html> </html>:** Raíz de todo el documento HTML.
+ **<head> </head>:** Contiene metadatos sobre la página, como el título.
+ **<body> </body>:** Contiene el contenido visible de la página.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apuntes HTML</title>
</head>
<body>
    
</body>
</html>
```
## Etiquetas basicas de HTMl
+ ``<h1><h2<h3><h4><h5><h6>`` Esta etiqueta hace referencia al tipo de encabezado que queremos utilizar, a mas grande queremos nuestro titulo de encabezado menor sera el numero, a mas pequeño utilizaremos un numero mayor
+ ``<p> </p>`` Esta etiqueta sirve para determinar que vamos a utilizar un parrafo de texto
+ ``<strong> </strong>`` Esta etiqueta sirve para poner las palabras que esten dentro de esta en NEGRITA
+ ``<em> </em>`` Esta etiqueta sirve para poner las palabras que esten dentro de esta en CURSIVA
+ ``<u></u>`` Esta etiqueta sirve para poner las palabras que esten dentro de esta SUBRAYADAS
+ ``<br>`` Esta etiqueta sirve para hacer un salto de linea
+ ``<hr>`` Esta etiqueta sirve para hacer una linea divisora en la pagina<li> </li> Esta etiqueta sirve para generar una lista, va  acompañado de las etiquetas <ol> y <li>
+ ``<ul> </ul>`` Esta etiqueta sirve para generar listas desordenadas por puntos
+ ``<ol> </ol>`` Esta etiqueta sirve para generar listas ordenada por numeros
+  ``<a> </a>`` Esta etiqueta sirve para generar un enlace 
+ ``<img> </img>`` Esta etiqueta sirve para introducir imagenes en nuestro documento, para ello necesitaremos de una ruta absoluta o una ruta relativa

