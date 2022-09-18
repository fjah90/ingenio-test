# Ingenio Test Full Stack

Repository para Prueba Full Stack Develper Ingenio. 
____________

## Requisitos para el código del FrontEnd


- Implemente un formulario de Autenticación de usuarios consumiendo el controlador de usuarios de la Web Api https://fakerestapi.azurewebsites.net/index.html 

- Cree una vista la cual permita realizar el consumo del servicio de sincronización de Autores Y libros. Se debe mostrar un mensaje (Modal) que indique el proceso ha finalizado. 

- Cree una vista la cual permita consultar los libros filtrados por autor y fecha de publicación (fecha inicio – fecha fin). El contenido de la respuesta deberá mostrarse sobre una tabla o grid que permita ornear por cualquier columna. 

- La aplicación debe permitir exportar el contenido de las tablas o grid a archivos de Excel.

### Puntos a considerar

- La aplicación deberá consumir los servicios implementados en el BACKEND.

- Considere la utilización de Frameworks como PRIME NG o Bootstrap.

## Requisitos para el código del BackEnd

- Cree una capa de acceso a datos que consuma información de una base de datos SQL Server como su repositorio de datos. 

- Cree una capa de lógica de negocios para que pueda recuperar la información de los Autores y Libros. 

- Cree un controlador WEB API que pueda devolver información para un autor determinado o Múltiples autores y Libros. 

- Implementa un Endpoint que permita sincronizar la información de los autores y libros desde la web api: https://fakerestapi.azurewebsites.net/index.html, la información obtenida deberá ser almacenada en una base de datos SQL Server (Debe considerar la creación del modelo de datos acorde a la información suministrada por la Api).

### Puntos a considerar

- La aplicación que cargue debería poder ejecutarse en un Visual Studio 2019 que usaremos para revisarlo. Evitar el uso externo herramientas / software que pueden causarnos problemas al revisar su solución.
 
- Para la implementación de esta prueba deberá realizar el consumo de servicio REST desde esta Web Api: https://fakerestapi.azurewebsites.net/index.html.

- Los servicios implementados deberán contar con autenticación con JWT.
