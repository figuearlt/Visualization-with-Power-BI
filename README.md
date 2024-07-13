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


## PROYECTO 2
### OBJETIVO

Generar métricas calculadas de una base de datos que registra los datos de empleados, activos e inactivos, de una compañía regional.

Se busca visualizar los según las siguientes preguntas:
	* Cantidad de empleados total
	* Cantidad de empleados activos
	* Cantidad de empleados inactivos

¿Cómo se va a calcular?

	* Medidas implícitas + panel de filtros
	* Medidas explícitas DAX

¿Qué visualizaciones vamos a utilizar?

	* Tarjetas
	* Segmentadores de datos
	* Gráfico circular
	* Gráfico de anillo
	* Gráfico de rectángulos
	* Mapas

### BASE DE DATOS
Considera las siguientes variables:

* ID de Empleado: Identificador único de Empleado. Presentado en formato texto.
* Función: Actividad laboral del empleado dentro del departamento respectivo. Presentado en formato texto.
* Departamento: Función principal de un sector dentro de la compañía. Presentado en formato texto.
* Región: Ubicación de la residencia del empleado. Presentado en formato texto.
* Educación: Nivel educativo del empleado, pudiendo ser Grado o Posgrado. Presentado en formato texto. 
* Género: Masculino, Femenino u Otro
* Jornada: Tipo de jornada laboral según Tipo de contrato (Tiempo Completo, Parcial, Medio Tiempo). Presentado en formato texto. 
* Modalidad: Formato de trabajo (Presencial o Remoto). Presentado en formato texto.
* Fecha Contratación: fecha en la cuál el trabajador ingresó a la compañía. Presentado en formato fecha 'dd-mmm-yy'.
* Estatus: Estado en el cual el empleado histórico se encuentra en la empresa ¿Continúa o no continúa trabajando allí? Presentado en formato texto.
* Feha Baja: Fecha en la cual el trabajador se le resindió el contrato y dejó de trabajar en la compañía. Presentado en formato fecha 'dd-mmm-yy'.