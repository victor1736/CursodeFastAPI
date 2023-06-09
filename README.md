# CursodeFastAPI
Curso de FastAPI de platzi sobre las peliculas

## Crear entorno virtual 
-	Python3 -m venv venv
Para activar mi entorno virtual 
-source venv/bin/actívate
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/b2c650ce-b2fe-48f1-a3ef-21911774dea6)

 
# Instalar fastapi
- pip install fastapi
Instalar uvicorn para poder lanzar el servidor 
- pip install uvircon
Comandos para llamar la librería  y asignarla a una variable para luego crear mi primer enpoint
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/72170a49-f40b-4169-8eff-10f467f91e92)
 
# Para activarlo con uvicron

![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/785ecf74-9e62-4eb9-bf05-bc2b717e67d2)
 
# Para ingresar a la documentación 

 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/8f710cba-c893-428f-b51b-1b41f69d96f4)

# Modificando el titulo y versión 

![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/692b94dc-789b-49b7-9c6a-19ff1897f2ac)

 Parte visual

 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/6bf28ae0-4d98-4d7e-b450-ac4fd6e1f774)
 
# Cambiando default por home 
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/c9db2895-a8db-424c-a669-4f1c777bbcc8)
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/d1409b8c-1c2e-4505-8c8f-4265e9f020d0)

# Para generar una visualización en HTML se   llama la librería 
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/6bb63d74-de58-4e61-8fb0-9c2e57125fc9)
 
Y se invoca donde la deseas aplicar con el lenguaje que corresponde a html
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/28911965-f7d6-40d1-974a-9d3205c6e92d)

La visualización en el  buscador 
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/bf31c330-8dfb-4084-9e0a-fe39274601e5)

#Get para visualizar películas que se encuentran en  mi lista 
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/52406d44-3438-425d-9bfa-7b5e00583366)

La lista con mi diccionario 
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/df31c37c-d816-4417-83e1-30a3c0e898c8)

# También puedo filtrar mis películas por id  de esta forma
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/f6d24c8c-7c25-4301-9a3a-b9f8918deaf5)

Así lo observamos en el navegador 
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/aa062b98-4706-4654-b374-b41d13bd014a)

esta es su respuesta en el navegador

![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/18945b7b-d611-43da-b532-01f3936636d0)

# Puedo buscarla como un parámetro query

![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/f1e9313f-102c-4a21-b181-8bb37a91842e)
 
La visualización den el buscador
Es esta 

 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/de1b1b17-4e1a-4639-855b-b2fb60084d0e)

# Para modificar un item  usamos el método put
En código se representa así 

![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/b05a6e79-936d-4f07-ab1a-d33c4acb4941)

 en el navegador se ve así 
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/3d0f2a14-fd73-4bc5-92ad-c1e3045ae6d3)

#Para eliminar un item de la lista  es de la siguiente forma el código  

![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/e98f5b28-e025-4b74-b80a-39e56c7a6f68)

y en e navegador se representa así 

![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/d114a502-c1fe-415a-9867-3f5811834222)
 
# Para generar squemas se hace uso de la librería pydantic y typinc 

![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/fc1a1e72-9824-48c5-b89e-10f2a296db24)
 
Agregamos una clase 

![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/86e6cfe4-bf64-4d0a-a9f5-7200c2aecc44)

 # Podemos cambiar el post y put  por menos líneas de código  donde en las entradas de la función pusimos la clase movie : Movie
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/a16eb48e-ee60-416d-98b8-17018c4a6b35)

## Para la validación agregamos  una nueva función 
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/82b1ef0b-2262-41c9-b09a-84d11f681f95)

La cual le dará limites a nuestros datos y puede agregar  textos que iran por defaul
En el cual usamos una clase para facilitar  las cosas 

![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/3ff2739a-3d78-4ce1-a9e2-8a4eac2cdf5d)

Para las autentificaciones de  parámetros de línea o query usamos nuevos componentes 
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/c70f3f89-7904-4d1e-a4c8-650667a52f8c)

# Para la búsqueda de información por id
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/f511f5a6-9f38-4133-9419-f096d3934cde)

para los parámetros query
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/08a15326-3b03-4017-afce-5743f50620da)
 
La autentificación hace referencia a la cantidad de parámetros o caracteres que puedo tener en cada una de nuestras descripciones y el tipo  con una entrada por default

#Tipos de Respuestas
Para un tipo de respuesta distinto que, cumpla con otras demandas o formatos en este caso utilizamos el tipo Json incluyendo la función de la librería indicada 
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/6b36d781-a192-4022-a98c-8a7a5b4d8922)

Pero también debemos indicar el tipo de respuesta desde un diccionario hasta una lista debemos ser muy específicos 
Esta la especificamos tanto en el CRUD como en la función dentro de esta 
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/e140199c-48c5-4905-9f14-43410472e9c8)
![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/0b17e7a7-e56d-4052-9ac2-4e025477a1c1)

Estos son algunos ejemplos, pero no son todos los que existen

# Códigos de estado

Con los códigos de estado indicamos lo que realizamos estos son algunos ejemplos
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/b60c822e-b5e3-4fa7-aec9-9c2d5bd2b071)

En el siguiente código si el no encuentra nada en la ubicación que le digo o la id  envia el código 404  
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/a212beb6-4ccd-4d51-bdb8-89a235f67afe)
![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/16c0e097-f3a2-49ce-9838-02de22dfb1cc)

## Flujo de autenticación
Ahora empezaremos con el módulo de autenticaciones pero antes quiero explicarte un poco acerca de lo que estaremos realizando en nuestra aplicación y cómo será el proceso de autenticación y autorización.
Ruta para iniciar sesión
Lo que obtendremos como resultado al final de este módulo es la protección de determinadas rutas de nuestra aplicación para las cuales solo se podrá acceder mediante el inicio de sesión del usuario. Para esto crearemos una ruta que utilice el método POST donde se solicitarán los datos como email y contraseña.
Creación y envío de token
Luego de que el usuario ingrese sus datos de sesión correctos este obtendrá un token que le servirá para enviarlo al momento de hacer una petición a una ruta protegida.

Validación de token
Al momento de que nuestra API reciba la petición del usuario, comprobará que este le haya enviado el token y validará si es correcto y le pertenece. Finalmente se le dará acceso a la ruta que está solicitando.
En la siguiente clase empezaremos con la creación de una función que nos va a permitir generar tokens usando la librería pyjwt.

## Instalar pyjwt para generar tokens
-pip install pyjwt
Para implementar un token de autentificación debo  crear un nuevo archivo 
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/bb1f1cb4-739f-4086-b1c2-b1db6528fd76)

En el cual llamaremos la librería y utilizaremos uno de sus servicios para crear el token 
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/aa7cd053-04d4-465b-a642-20d5d7d7ee64)

generaremos una entrada tipo post para el login independiente de movies y home
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/447d1b40-ef3a-4d36-9d01-735d2a7f14c8)

En el buscador o navegador se ve de la siguiente forma
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/b0ddf393-bfc8-44b1-85a1-f3e65e962cfd)

# Para validar mi token
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/bda39edf-563e-4b63-a38b-9e4f0805cf3c)

también modificamos el archivo jwt para decodificar la respuesta
 
 ![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/ed3089f0-9263-4969-880c-0333ed261d92)

Con su respectiva respuesta  

![image](https://github.com/victor1736/CursodeFastAPI/assets/82006043/ba205748-b872-47fb-959a-8c53e66df309)

