# Proyecto_DS_CodigoFacilito
Proyecto Final para el bootcamp de Data Science en Codigo Facilito
## Composicion
* Se tienen un archivo de analisis previo, donde se revisa el alcance del proyecto, definiciendo que tipo de rotacion debo analizar segun el comportamiento estadisticamente encontrado
* El segundo archivo es el analisis de grupal, donde se hace unos joins, limpieza y prediccion con el modelo
* El pdf de la presentacion a modo resumen de los dos ipynb de analisis

## Antecentes - Variables
La empresa se dedica a la venta de intangibles con dos principales productos.
* Los productos de venta individual son otorgados a personas natuales
* Los productos de venta grupal son otorgados a varias personas que conforman un grupo
Debido a la competencia del sector, la empresa suele competir con otras compañias por tratar de tener los mejores colaboradores con una rotacion menor a la del mercado.

## Bases a Utilizar
* Link a las bases de datos se encuentran en el ipynb alojados en drive
### 1. Planilla:
* Importancia: 
    * Base de colaboradores y el area de donde pertenecen desde el 2018 al 2021 
    * Es el archivo madre desde donde trabajar porque tiene todos los colaboradores
* Variables a usar:
    * MES, COD, Cargo, Oficina, Producto, Territorio y Zona
### 2. Entrevistas Ceses
* Importancia: 
    * Reporte de Encuestas hechas a cesados en el proceso de salida de la empresa
* Variables a usar:
    * CESE, Ingreso, COD, Cargo, Motivo, tipo de cese
### 3. Programa de mejora
* Importancia: 
    * Base de colaboradores que entraron al programa de mejora y su tiempo de permanencia. si no cumple con el programa el colaborador es invitado a retirarse.
* Variables a usar:
    * Codigo, motivo, fecha inicio programa
### 4. Memorandum
* Importancia: 
    * Lista de memorandums aplicados a los colaboradores por diferentes tipos de falta
* Variables a usar:
    * Codigo, Cargo
### 5. Bonos Venta Individual y grupal
* Importancia: 
    * Bono otorgado por cumplir ciertas reglas y metas en las ventas del mes en individual y Grupal
* Variables a usar:
    * CESE, Ingreso, COD, Cargo
### 6. Hijos total
* Importancia: 
    * Nro de vacaciones acumuladas por no tomarlas cuando correspondia, al ano se se deberian tomar 30 dias de vacaciones
* Variables a usar:
    * CESE, Ingreso, COD, Cargo, fecha nacimiento
### 7. Info personal
* Importancia: 
    * Nro de vacaciones acumuladas por no tomarlas cuando correspondia, al ano se se deberian tomar 30 dias de vacaciones
* Variables a usar:
    * CESE, Ingreso, COD, Cargo, estado civil, educacion
