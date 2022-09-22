## EJERCICIO INMOBILIARIA

1. Crear un proyecto con el nombre "proyecto-inmobiliaria", lo cual implica:
   a. Crear la carpeta con el nombre mencionado
   b. Dentro de la carpeta crear el archivo index.js
   c. Ejecutar el comando correspondiente para crear el archivo package.json
   d. Instalar los siguientes paquetes en el proyecto: express, nodemon, body-parser
   e. En el package.json generar los scripts necesarios para ejecutar el proyecto.

2. Crear un archivo .js con el nombre "inmuebles" y dentro de ella crear un array que contenga los inmuebles del archivo inmuebles.txt. (No olvidar de exportar el array).

3. En index.js crear un servidor utilizando "express", que escuche en el puerto 3001 y mediante consola mostrar el puerto.

4. Dentro del index.js vamos a crear los siguientes puntos de acceso con sus respectivas funcionalidades (RECOMIENDO UTILIZAR POSTMAN O ALGUNA HERRAMIENTA SIMILAR PARA REALIZAR LAS PRUEBAS):
   a. Method: GET, PA: "/". Debe mostrar un mensaje en el browser que diga "Bienvenidos a INMUEBLES SRL".
   b. Method: GET, PA: "/api/inmuebles". Debe mostrar en el browser todos los inmuebles.
   c. Method: GET, PA: "/api/inmuebles/:id". Debe mostrar en el browser el inmueble con el id indicado.
   d. Method: POST, PA: "/api/inmuebles/nuevo". Debe crear un nuevo inmueble y luego mostrar todos en pantalla.
   e. Method: PUT, PA: "/api/inmuebles/editar/:id". Debe editar uno o más atributos del inmueble pasado por parámetro, y mostrarlo en pantalla.
   f. Method: DELETE, PA: "/api/inmuebles/eliminar/:id". Debe eliminar el inmueble pasado por parámetro y mostra la lista resultante en pantalla.
   g. Method: GET, PA: "/api/inmuebles/filtro". Debe mostrase en pantalla aquellos inmuebles que respondan a los filtros de: metrosCuadrados y/o precio pasados mediante body.
   h. Method: GET, PA: "/api/inmuebles/info". Debe mostrase en pantalla un mensaje que describa la cantidad de inmuebles existentes y fecha y hora en al que se realizó la consulta.

5. Crear un archivo .js que contenga un array de permisos (tipoUsuario, permiso).

6. Crear una función middleware que dependiendo del tipo de usuario que realice la petición, le permita acceder o no al mismo (en este últmo caso visualizar el siguiente mensaje "Usted no posee permisos para está petición"), teniendo en cuenta lo siguiente:
   a. Todos los tipos de usuarios deben tener acceso al PA: "/";
   b. El tipo de usuario 1 va a tener acceso solamente a los puntos del A a la D.
   c. El tipo de usuario 2 va a tener acceso solamente a los puntos del E a la G.
   d. El tipo de usuario 3 va a tener acceso solamente al punto H.

7. Subir a un repositorio y en enviar el link del mismo al correo: ing.ezequielsoruco@gmail.com.
