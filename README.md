# CursodeFastAPI
Curso de FastAPI de platzi sobre las peliculas

##Crear entorno virtual comando 
-	Python3 -m venv venv
Para activar mi entorno virtual 
-source venv/bin/actívate
 
##Instalar fastapi
- pip install fastapi
Instalar uvicorn para poder lanzar el servidor 
- pip install uvircon
Comandos para llamar la librería  y asignarla a una variable para luego crear mi primer enpoint
 
##Para activarlo con uvicron
 
##Para ingresar a la documentación 
 
##Modificando el titulo y versión 
 
Parte visual
 
##Cambiando default por home 
 
 

##Para generar una visualización en HTML se   llama la librería 
 
Y se invoca donde la deseas aplicar con el lenguaje que corresponde a html
 
 
La visualización en el  buscador 
 
##Get para visualizar películas que se encuentran en  mi lista 
 
La lista con mi diccionario 
 
##También puedo filtrar mis películas por id  de esta forma
 
Así lo observamos en el navegador 
 
Y esta es su respuesta  
##Puedo buscarla como un parámetro query
 
La visualización den el buscador
Es esta 
 
##Para modificar un item  usamos el método put
En código se representa así 
 en el navegador se ve así  
##Para eliminar un item de la lista  es de la siguiente forma el código   
y en e navegador se representa así 
 
##Para generar squemas se hace uso de la librería pydantic y typinc 
 
Agregamos una clase 
 
##Podemos cambiar el post y put  por menos líneas de código  donde en las entradas de la función pusimos la clase movie : Movie
 
 
##Para la validación agregamos  una nueva función 
 
La cual le dará limites a nuestros datos y puede agregar  textos que iran por defaul
En el cual usamos una clase para facilitar  las cosas  
Para las autentificaciones de  parámetros de línea o query usamos nuevos componentes 
 
##Para la búsqueda de información por id
 
Y para los parámetros query
 
##La autentificación hace referencia a la cantidad de parámetros o caracteres que puedo tener en cada una de nuestras descripciones y el tipo  con una entrada por default

Tipos de Respuestas
Para un tipo de respuesta distinto que, cumpla con otras demandas o formatos en este caso utilizamos el tipo Json incluyendo la función de la librería indicada 
 
Pero también debemos indicar el tipo de respuesta desde un diccionario hasta una lista debemos ser muy específicos 
Esta la especificamos tanto en el CRUD como en la función dentro de esta 
 
 
Estos son algunos ejemplos, pero no son todos los que existen

Códigos de estado

Con los códigos de estado indicamos lo que realizamos estos son algunos ejemplos
 
En el siguiente código si el no encuentra nada en la ubicación que le digo o la id  envia el código 404  
 
##Flujo de autenticación
Ahora empezaremos con el módulo de autenticaciones pero antes quiero explicarte un poco acerca de lo que estaremos realizando en nuestra aplicación y cómo será el proceso de autenticación y autorización.
Ruta para iniciar sesión
Lo que obtendremos como resultado al final de este módulo es la protección de determinadas rutas de nuestra aplicación para las cuales solo se podrá acceder mediante el inicio de sesión del usuario. Para esto crearemos una ruta que utilice el método POST donde se solicitarán los datos como email y contraseña.
Creación y envío de token
Luego de que el usuario ingrese sus datos de sesión correctos este obtendrá un token que le servirá para enviarlo al momento de hacer una petición a una ruta protegida.

Validación de token
Al momento de que nuestra API reciba la petición del usuario, comprobará que este le haya enviado el token y validará si es correcto y le pertenece. Finalmente se le dará acceso a la ruta que está solicitando.
En la siguiente clase empezaremos con la creación de una función que nos va a permitir generar tokens usando la librería pyjwt.

##Instalar pyjwt para generar tokens
-pip install pyjwt
Para implementar un token de autentificación debo  crear un nuevo archivo 
 
En el cual llamaremos la librería y utilizaremos uno de sus servicios para crear el token 
 
Y generaremos una entrada tipo post para el login independiente de movies y home
 
En el buscador o navegador se ve de la siguiente forma
 
##Para validar mi token
 
Y también modificamos el archivo jwt para decodificar la respuesta
 
Con su respectiva respuesta  

