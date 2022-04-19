# Proyecto Employee Turnover

## Motivación

La rotación en las empresas suele ser un pain, pues el cese de un colaborador siempre generará costos no planeados
Este impacto aumenta cuando el cese se da en puestos claves para negocio
** Para la empresa de este proyecto detectar los motivos de cese y predecir la rotación es principalente importante, ya que la industria donde se encuentra tiene bastante competencia y por ende mucha oferta de trabajo **

## Definición de Cese

En la primera estapa del proyecto definicimos el cese a analizar según su comporamiento histórico
  * Solo se anaizarán ceses volunatarios
  * Algunos motivos de ceses
  * Y una antiguedad mayor a 9 meses

## Variables a utilizar

### 1. Planilla:
  * Base de colaboradores y el area de donde pertenecen desde el 2018 al 2021 
  * Es el archivo base desde donde se trabajara
### 2. Entrevistas Ceses
  * Reporte de Encuestas hechas a cesados en el proceso de salida de la empresa
  * Se utilian la variables motivo de cese, antiguedad y tipo de cese
### 3. Programa de mejora
  * Base de colaboradores que entraron al programa de mejora por bajo desempeño o alguna indiciplina.
  * Nro de veces que entro al prorama de mejora
### 4. Memorandum
  * Lista de memorandums aplicados a los colaboradores por diferentes tipos de falta
  * Nro de Memoradums que tiene el colaborador
### 5. Bonos Venta
  * Bono otorgado (aparte del sueldo) por cumplir con las ventas
  * Bono promedio histórico, Desviación estandar de los bonos recibidos, Nro de veces que obtuvo un bono menor al 25% (1er cuartil)
### 6. Hijos total
  * Nro de hijos que tiene cada colaboradores
  * Total de hijos menores a 18 años
### 7. Info personal
  * Informacon basica del colaborador
  * Edad, Sexo, Antiguedad, estado civil y nivel educacion
### 8. Desempeño
  * Desmpeño mensual el colaborador en el tiempo
  * Desmpeño promedio histórico, Desviación estandar del Desmpeño, Nro de veces que obtuvo un Desmpeño menor al 25% (1er cuartil)
### 9. Descanso medico
  * Lista de colaboradores que tuvieron descanso medico
  * Suma total de dias de Descanso Medico

## Conclusiones

* Se realizó una regresión logistica para detectar la probabilidad que un colaborador cese
* Se detectaron las principales variables que influyen en la rotación directamente o inversamente
