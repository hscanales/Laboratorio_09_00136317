
    ¿Cuál es la principal función del módulo HTTP?
    R// Permite transmitir a Node.js informacion por medio del protocolo HTTP
    ¿Cuál es la principal función del módulo FileSystem?
    R// File System provee una API para trabajar con los archivos del sistema de una manera mas cerca
    ¿Qué es un MIME type?
    R// Es un estandar de internet para interpretar el tipo de contenido de los mensajes

    
    ¿Qué contienen las variables "req" y "res" en la creación del servidor?
    R// req tiene la peticion que realizo el usuario y res tiene la respuesta que el servidor le enviara al usuario
    ¿La instrucción .listen(number) puede fallar? Justifique.
    R// Si debido a que nunca se puede tener varias cosas escuchando al mismo puerto
    ¿Por qué es útil la función "collectRequestData(...)"?
    R// Esta es la que recolecta y une todos los pedacitos de los paquetes

    
    ¿Para qué, además de conocer la dirección de la petición, es útil la variable "pathname"?
    R// Direcciona al usario

    ¿Qué contine el parametro "data"?
    R// Contiene la informacion que recibio en el request

    ¿Cuál es la diferencia entre brindar una respuesta HTML y brindar una CSS? 
    R// Debido a que el MIME 

     ¿Qué contiene la variable "result"?
     R// Tiene los resultados del formulario

      ¿Por qué con la variable "data" se debe aplicarse el metodo toString()? Justifique.
      R//  Ya que si es cierto el tiene el contenido del archivo pero en buffer con lo cual se debe parsear a String.

    ¿Hay diferencia al quitar el control de peticiones para hojas CSS? Si sucedió algo distinto justifique por qué.
    R// El servidor no sabe que tipo de formato era el archivo entonces no lo aplica como css

    ¿Se puede inciar el servidor (node main.js) en cualquier sitio del proyecto? Cualquier respuesta justifique.
    R//No, debido a que node busca el js en la ruta donde esta actualmente desde consola

     Con sus palabras, ¿Por qué es importante aprender Node.js sin el uso de frameworks a pesar que estos facilitan el manejo de API's?
    R// Cuando Aprendemos a usar node js sin frameworks nosotros entendemos el interior de lo que hace cada framework, y asi nosotros podemos comprender a profundidad todo
     