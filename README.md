# App_Actix-AND-Yew
Realizacion de una Api rest en Actix con Front-end en Yew, es una aplicacion de programacion de series y peliculas.
Para los estilos se utilizo la libreria de Tailwindcss.


# RUN
## Actix
Para poder ejecutar en back-end en actix utilizaremos
 ### cargo r -r

## Yew
 Para ejecutar el Fron-end en Yew, utilizaremos 
 ### trunk serve

 Esto inicializara ambas partes del programa.


 # API

Con la api se pueden realizar pruebas a traves de postman u otro servicio de pruebas.
 
 ## AGREGAR UN NUEVO DATO
Para agregar un nuevo dato haremos de la siguiente:

{
  "id":3,
	"title":"Espiritu Indomable",
	"description": "Pelicula Familiar A",
	"code": "B1000000" ,
	"hour":"3:00 PM"
}

# END POINTS

## GET
http://localhost:8081/todolist/entries

## POST
http://localhost:8081/todolist/entries

## PUT
http://localhost:8081/todolist/entries/{} <---- Sustituir las llaves "{}", por el id del registro que se desea manipular.

## DELETE
http://localhost:8081/todolist/entries/{}  <---- Sustituir las llaves "{}", por el id del registro que se desea manipular.







 
