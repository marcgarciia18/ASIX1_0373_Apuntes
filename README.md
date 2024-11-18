# ASIX1_0373_Apuntes

## INDICE_DE_APUNTES
+ [MARKDOWN](#markdown)
+ [GIT](#git)
+ [GITHUB](#github)
+ [HTML](#html)
___

# [MARKDOWN](#indice_de_apuntes)

## ¿Qué es Markdown?
Markdown es un lenguaje de marcado ligero diseñado para hacer que la escritura y el formato de texto sean más fáciles y legibles

## Encabezados
Markdown nos ofrece una forma sencilla y flexible de crear encabezados en los documentos permitiendo organizar el contenido de manera clara y jerárquica, existen distintos tipos de encabezados:

+ H1: Se utiliza para el título principal de un documento o sección. Se representa con un solo numeral (#)

# Este es un encabezado de nivel 1 (H1)

+ H2: Se utiliza para subtítulos o títulos de secciones secundarias. Se representa con dos numerales (##)

## Este es un encabezado de nivel 2 (H2)

+ H3: Se utiliza para subtítulos de nivel inferior. Se representa con tres numerales (###)

### Este es un encabezado de nivel 3 (H3)

+ H4, H5, H6: Se utilizan para encabezados de niveles aún más bajos, siguiendo la misma lógica.

#### Este es un encabezado de nivel 4 (H4)

##### Este es un encabezado de nivel 5 (H5)

###### Este es un encabezado de nivel 6 (H6)


## Listas
En markdown se pueden crear listas tanto ordenadas como desordenadas, para ello utilizaremos un orden numerico en caso de querer nuestra lista ordenada o utilizaremos los caracteres "* , + , -" en caso de querer una lista desordenada

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

## Insercion de codigo
Para insertar codigo en markdown y que se pueda mostrar en pantalla utilizaremos ``` para abrir nuestra "etiqueta" y otras tres para cerrar, añadiendo dentro el codigo

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ASIX1 CODIGO PANTALLA MARKDOWN</title>
</head>
<body>
    
</body>
</html>
```

## Insercion de links
En referencia a los links existe una manera de hacerlo, abriremos corchetes para escribir el texto que aparecera en el link que pulsaremos, luego abriremos parentesis para añadir la URL de esta y entre comillas un texto opcional para cuando tengamos el cursor encima del texto

```[textoclick](URL "TituloOpcional")```

[Pagina web de Jesuites Bellvitge](https://www.fje.edu/ca/jesuites-bellvitge "Jesuites")

## Insercion de imagenes
Para la insercion de imagenes utilizaremos un metodo bastante parecido al de los links, primero abriremos corchetes para escribir el nombre de dicha imagen, luego abriremos parentesis para añadir la url de la imagen que previamente habremos subido a github y para acabar pondremos comillas con un texto por si la imagen falla y no carga en nuestra web

```[tituloimagen](URL "TituloOpcional")```
![JcReyes](https://github.com/marcgarciia18/ASIX1_AprendizajeMarkdown/blob/main/Imagenes/JC.jpg "ReyDeEspaña")

## Tablas

|Titulo 1 | Titulo 2 | Titulo 3 |
|:----------:|:---------------:|:----------:|
|SMX2|Curso 23-24 |25|
|**ASIX1**|Curso 24-25|33|
|DAW2|Curso 24-25|29|

___

# [GIT](#indice_de_apuntes)
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

# [GITHUB](#indice_de_apuntes)
GitHub es una plataforma de desarrollo colaborativo que utiliza el sistema de control de versiones Git. Permite a los desarrolladores almacenar, compartir y trabajar en proyectos de código fuente de manera conjunta

## Como crear un repositorio

1. Deberemos darle a **_create new repositor_**

![RepositorioNuevo](https://github.com/marcgarciia18/ASIX1_0373_Apuntes/blob/main/img/crear_repo.png "Crear nuevo repositorio")

2. Configuraremos el repositorio con cosas como pueden ser:
    + Nombre del repositorio
    + Descripcion adicional para este
    + Decidir si hacerlo publico o no
    + Inicializar el repositorio
    + Añadir un README al repositorio
![RepositorioConfigurado](https://github.com/marcgarciia18/ASIX1_0373_Apuntes/blob/main/img/nuevo_repo.png "Configurar nuevo repositorio")


## Como clonar un repositorio
Para clonar un repositorio en github deberemos seguir los siguientes pasos:
1. Deberemos obtener nuestra _URL_ del repositorio que queremos clonar, para ello debe estar creado previamente y una vez lo tengamos deberemos acceder al **_boton verde "CODE"_** y en el desplegable veremos la url en _HTTPS_, copiaremos esta para luego

![URLRepositorio](https://github.com/marcgarciia18/ASIX1_0373_Apuntes/blob/main/img/url_clonar.png "URL para clonar repositorio")

2. Una vez con la _URL_ deberemos ir a nuestro **_CMD_** para poder clonarlo, una vez dentro de este deberemos buscar la carpeta donde tenemos nuestro repositorio

![CarpetaRepositorio](https://github.com/marcgarciia18/ASIX1_0373_Apuntes/blob/main/img/cmd_repo.png "Carpeta donde esta repositorio")

3. Cuando estemos dentro de la carpeta deberemos utilizar el siguiente comando -> **_git clone "pegar url"_** 


![Comando](https://github.com/marcgarciia18/ASIX1_0373_Apuntes/blob/main/img/git_clone.png "Comando git clone")

4. Finalmente ya tendremos clonado el repositorio que se encuentra en red en local.

![RepositorioClonado](https://github.com/marcgarciia18/ASIX1_0373_Apuntes/blob/main/img/repo_clonado.png "Repositorio clonado en local")

___

# [HTML](#indice_de_apuntes)

## Introduccion a HTML

### ¿Qué es HTML?

HTML (HyperText Markup Language) es el lenguaje estándar para crear páginas web. Imagina que es como un conjunto de bloques de construcción que te permiten estructurar y dar formato al contenido de una página web. Estos bloques se llaman "etiquetas".

### ¿Para que sirve HTML?

+ **Organizar el contenido:** Define la estructura de una página, como encabezados, párrafos, listas, tablas, etc.
+ **Incluir multimedia:** Permite insertar imágenes, videos, audio y otros elementos multimedia en una página.
+ **Crear enlaces:** Crea vínculos a otras páginas web o a diferentes secciones de la misma página.
++ **Dar formato:** Aunque de forma básica, puedes aplicar negrita, cursiva y otros estilos simples al texto.

## Estructura basica de HTML

+ **``<!DOCTYPE html>``:** Declara el tipo de documento.
+ **``<html> </html>``:** Raíz de todo el documento HTML.
+ **``<head> </head>``:** Contiene metadatos sobre la página, como el título.
+ **``<body> </body>``:** Contiene el contenido visible de la página.

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

+ **``<h1><h2<h3><h4><h5><h6>`` Esta etiqueta hace referencia al tipo de encabezado que queremos utilizar, a mas grande queremos nuestro titulo de encabezado menor sera el numero, a mas pequeño utilizaremos un numero mayor
+ **``<p> </p>``** Esta etiqueta sirve para determinar que vamos a utilizar un parrafo de texto
+ **``<strong> </strong>``** Esta etiqueta sirve para poner las palabras que esten dentro de esta en NEGRITA
+ **``<em> </em>``** Esta etiqueta sirve para poner las palabras que esten dentro de esta en CURSIVA
+ **``<u></u>``** Esta etiqueta sirve para poner las palabras que esten dentro de esta SUBRAYADAS
+ **``<br>``** Esta etiqueta sirve para hacer un salto de linea
+ **``<hr>``** Esta etiqueta sirve para hacer una linea divisora en la pagina 
+ **``<li> </li>``** Esta etiqueta sirve para generar una lista, va  acompañado de las etiquetas ``<ol> y <li>``
+ **``<ul> </ul>``** Esta etiqueta sirve para generar listas desordenadas por puntos
+ **``<ol> </ol>``** Esta etiqueta sirve para generar listas ordenada por numeros
+ ** ``<a> </a>``** Esta etiqueta sirve para generar un enlace 
+ **``<img> </img>``** Esta etiqueta sirve para introducir imagenes en nuestro documento, para ello necesitaremos de una ruta absoluta o una ruta relativa

## Rutas

En HTML cuando necesitamos enlazar a otros documentos, ya sean documentos HTML, hojas CSS o imagenes podemos utilizar las rutas para especificar la ubicacion de estos archivos.
Existen dos tipos de rutas:
* **Rutas Absolutas:** Estas especifican la ubicacion al completo del archivo, empezando desdee  el dominio. ``<img src="ubicacionprincipal/carpetadondeseencuentra/archivoaenlazar">``
* **Rutas Relativas** Estas especifican la ubicacion al archivo respecto a donde nos encontramos, si necesitamos movernos entre estas utilizaremos un "." o ".." ``<img src="./img/imagen1>`` | ``<img src ="../img/imagen2>``

## Elementos semanticos en HTML

Los elementos semanticos en HTML son aquellos que indican el proposito de diferentes  secciones de la pagina web
Los elementos mas a destacar son: 

+ **``<header>``** Representa el encabezado de una sección o página, generalmente contiene el título y la navegación principal.
+ **``<footer>``** Representa el pie de página de una sección o página, generalmente contiene información de copyright, enlaces a políticas de privacidad, etc.
+ **``<article>``** Define un artículo independiente, como una publicación de blog o un artículo de noticias.
+ **``<section>``** Representa una sección genérica de contenido.
+ **``<nav>``**  Define una sección de navegación, como un menú.
+ **``<figure>``** Define una unidad de contenido autocontenido, como una imagen, un diagrama, una cita, etc.

![SemanticaHTML](https://github.com/marcgarciia18/ASIX1_0373_Apuntes/blob/main/img/html_semantico.png "Elementos Semanticos HTML")


## Formularios

Los formularios web sirven para interactuar con el usuario y que este pueda darnos cierta informacion. Esta informacion sirve para ser procesada segun la necesidad que tenga nuestra pagina web
Estos formularios utilizan unas etiquetas especificas:
+ **``<form> </form>``** Se utiliza para crear formularios  que permitan al usuario enviar datos
+ **``<input> </input>``** Sirve para crear distintos tipos de campos 
    + **``RADIO``** Boton de opcion que se agrupa con otros del mismo nombre
    + **``CHECKBOX``** Casilla de verificacion 
    + **``type``** Define el tipo de entrada que se  va a mostrar
    + **``id``** Identificador unico para el campo
    + **``name``** Nombre del campo de entrada
    + **``value``** Valor predeterminado del campo o el valor enviado
    + **``placeholder``** Texto que aparece en el campo cuando esta vacio
    + **``disabled``** Desactiva el campo, evitando que el usuario interactue con el
    + **``required``** Indica que el campo debe completarse antes de ser enviado
    + **``readonly``** Hace que el campo sea solo de lectura
+ **``<label>``** Proporciona una etiqueta para un elemento del formulario
+ **``<fieldset> </fieldset>``** Agrupa secciones del formulario en un recuadro

### **EJEMPLO DE FORMULARIO**
Este tipo de formulario tiene varias partes, la primera nos pedira que escribamos un nombre y una contraseña, la segunda parte nos pedira que seleccionemos el idioma que hablamos y nuestra nacionalidad

**_Parte1_**

![FormularioHTML](https://github.com/marcgarciia18/ASIX1_0373_Apuntes/blob/main/img/formulario1.png "Formulario1")

**_Parte2_**

![FormularioHTML](https://github.com/marcgarciia18/ASIX1_0373_Apuntes/blob/main/img/formulario1.png "Formulario2")

#### _Codigo del formulario_
```
    <form action="recepcion.php" method="GET">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" placeholder="Introduce tu nombre"><br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Introduce tu contraeña"><br><br>

        <fieldset>
            <legend>Idioma</legend>
            <input type="radio" id="Brazilian" name="idioma" value="Brazilian">
            <label for="Brazilian">Brazilian</label>
    
            <input type="radio" id="Portuguese" name="idioma" value="Portuguese">
            <label for="Portuguese">Portuguese</label>
        
        </fieldset>

        <fieldset>
            <legend>Nacionalidad</legend>
            <input type="checkbox" id="Brazilian" name="idioma" value="Brazilian">
            <label for="Brazilian">Brazilian</label>
    
            <input type="checkbox" id="Portuguese" name="idioma" value="Portuguese">
            <label for="Portuguese">Portuguese</label>
        </fieldset> 
```
