# VISUALIZACIÓN POWER BI

## PROYECTO 1
### OBJETIVO

Dashboard en Power BI que utiliza una base de datos ficticia para el análisis visual de sus clientes, entre los años 2005 a 2021, la cual 
ya pasó por una etapa de limpieza y transformación.

Se busca visualizar los según las siguientes preguntas:
	* ¿Cuál es la proporción, según el tipo de clientes?
	* ¿Cuál es el número de clientes que son datos de alta por año, según su tipo?
	* ¿Cuál es la edad de los clientes, según su tipo?
	* ¿Cuál es el origen de los clientes, según su tipo?
	* ¿Cuál es el número de contacto de los clientes?



### BASE DE DATOS
Considera las siguientes variables:

* ID de Cliente: Identificador único de Cliente. Presentado en formato texto.
* Nombre Completo: Nombre del Cliente, considerando los dos nombres y los dos apellidos. Presentado en formato texto.
* Ciudad: Ciudad de origen del cliente. Presentado en formato texto.
* Dirección: ubicación de la residencia del cliente. Presentado en formato texto.
* Edad: Edad del cliente, presentado en números enteros.
* Teléfono: Número telefónico de residencia del cliente. Presentado en formato texto.
* Año de alta: Extraído de Fecha de alta, considera únicamente el año en que el cliente fue dado de alta. Presentado en formato de texto.
* Grupo de cliente: Clasificación interna del servicio de salud que define al cliente según ciertos criterios:
	* O : Cliente ocasional. Clientes que compran por primera vez o lo hacen ocasionalmente, pero sin una frecuencia establecida.
	* F : Clientes de compra frecuente.
	* R : Cliente de compra regular.
	* E : Clientes-embajadores - Una persona que recomienda el producto.
