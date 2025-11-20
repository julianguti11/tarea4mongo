Fase 2. MongoDB:
En la actualidad, muchas aplicaciones requieren almacenar grandes volúmenes de información que cambia con frecuencia y no siempre sigue una estructura rígida. Por esta razón, las bases de datos NoSQL se han convertido en una alternativa importante frente a los modelos relacionales tradicionales. Entre ellas, MongoDB destaca por su flexibilidad, su modelo basado en documentos y su facilidad para trabajar con datos semi-estructurados.
En este trabajo se desarrolla un ejercicio práctico utilizando MongoDB para gestionar un catálogo de productos colombianos. A través de este caso de uso, se busca comprender cómo se diseñan las colecciones, cómo se insertan documentos y cómo se realizan consultas básicas, avanzadas y de agregación. Este proceso permite fortalecer conocimientos fundamentales sobre bases de datos NoSQL y su aplicación en escenarios reales.

Diseño de la base de datos

Caso de Uso 
Se crea una tienda online de productos colombianos como caso de uso
El caso de uso seleccionado consiste en administrar un catálogo de productos colombianos dentro de una aplicación que necesita almacenar y consultar información de manera flexible. Este escenario es ideal para usar MongoDB, ya que los productos pueden tener características que cambian con el tiempo y no siempre siguen una estructura fija.
El catálogo contiene productos típicos del mercado colombiano, cada uno representado como un documento con los siguientes campos:
•	nombre: nombre del producto (ej. “Café de origen Nariño”).
•	categoria: tipo o grupo al que pertenece (ej. “Café”, “Frutas”, “Dulces”).
•	precio: valor en pesos colombianos.
•	disponible: indica si el producto está activo o en inventario.

Nombre de la base de datos: Tienda 

Nombre de la colección: productos_colombianos

Implementación en MongoDB: 
• Crear una base de datos en MongoDB e insertar un conjunto de datos de prueba (al menos 100 documentos).

Conclusiones
•	Este trabajo me permitió comprender mejor cómo funciona MongoDB y cómo se organizan los datos mediante documentos en lugar de tablas, lo cual facilita trabajar con información flexible.

•	Al realizar las consultas básicas pude entender el proceso esencial para manejar datos dentro de una colección: insertar nuevos productos, seleccionarlos, actualizarlos y eliminarlos cuando es necesario.

•	Las consultas con filtros y operadores demostraron que es posible obtener información más precisa aplicando condiciones específicas, especialmente cuando se trabaja con grandes cantidades de datos.

•	Las consultas de agregación permitieron analizar los productos desde un enfoque más estadístico, obteniendo totales, sumas, promedios y valores mínimos y máximos, lo que demuestra que MongoDB también es útil para interpretar datos.

•	En general, el uso de MongoDB resultó práctico y adecuado para trabajar con información variada y este proyecto reforzó mis conocimientos básicos sobre bases de datos NoSQL y sus aplicaciones.
