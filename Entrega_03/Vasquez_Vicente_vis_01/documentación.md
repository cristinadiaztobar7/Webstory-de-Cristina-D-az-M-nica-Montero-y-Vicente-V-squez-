# Documentación

## 1. Proceso de visualización  

Para la elaboración de la visualización se trabajó con dos archivo inicial en formato Excel, el cual contiene la información sobre atletas chilenos entre el año 2022 y 2025 que recibieron la beca PRODDAR, además de los montos ingresados según el DIPRES y la Ley de Presupuestos en el Instituto del Deporte y Ministerio del deporte entre el año 2000 y el 2025

### Pasos realizados:
1. Investigación y recopilación de datos.
2. Creación de dos bases de datos en formato Excel y CSV.
3. Elaboración dos gráficos representaticos de cada base de datos.

### Decisiones tomadas:
- Se optó por el formato **CSV** debido a su fácil capacidad de comprensión en comparación con otros formatos. 
- Se hicieron ambas bases de datos desde cero ya que fue una variable que se sumó dentro de la hipótesis 
- Todos los datos ingresados fueron sacados de documentación pública y oficial por parte del Estado.

---

## 2. Base de datos utilizada  

- **Archivo:** PRESUPUESTO ANUAL DEPORTE.csv  
- **Procesamiento:** Realización de limpieza de base de datos de forma manual.  
- **Motivo de selección:** Tiene como finalidad ver el impacto que tiene el presupuesto utilizado durante cada año para los deportes en el resultado de los atletas chilenos, así como las becas a las que optan. 

---

## 3. Posibles preguntas de la visualización  

Algunas preguntas que la visualización puede responder:  
- ¿En qué año hubo un mayor ingreso de presupuesto? 
- ¿Cómo ha incrementado la cantidad de atletas becados durante los últimos años?
- ¿Cómo ha variado el monto de las becas dentro del mismo año o a través de estos?

---

## 4. Ficha técnica de la base de datos  

PRESUPUESTO ANUAL DEPORTE
BENEFICIARIOS BECA PRODDAR 

**Descripción:**  
Dataset con información sobre el presupuesto recibido por el Ministerio del Deporte y el Instituto Nacional del Deporte entre el año 2000 y el 2003.

Dataset con la cantidad de beneficiarios de la beca PRODDAR y sus respectivos montos entre 2022 y 2025

**Cobertura temporal:**  
Años registrados en la columna **Año** (ejemplo: 2022–2023).  

**Cobertura geográfica:**  
Principalmente Chile.  

### Variables incluidas  


| Variable     | Descripción                          |
|--------------|--------------------------------------|
| **Nombre**   | Nombre del atleta         |
| **Apellido**     | Apellido del atleta                 |
| **Sexo** | Sexo del postulante           |
| **Monto**     | Nacionalidad de la atleta            |
| **Mes**    | Mes donde estaba activa la beca        |
| **Año**      | Año donde estaba activa la beca            |

| Variable     | Descripción                          |
|--------------|--------------------------------------|
| **Año**   | Nombre completo de la atleta         |
| **Ingreso Subsecretaría del Deporte**     |  ingreso solo para la Subsecretaría                 |
| **INGRESO INSTITUTO NACIONAL DE DEPORTE (EN MILES DE PESOS)** | ingreso solo para el IND             |
| **PRESUPUESTO TOTAL (EN MILES DE PESOS)**     | Ingreso total en deporte          |

### Observaciones  
- Las  
- El dataset está diseñado para análisis exploratorios de rendimiento deportivo femenino en Chile.  

---

## 5. Archivos entregados  

-  `mujeres.csv` → Base de datos limpia en formato CSV  
- `README.md` → Documentación individual y ficha técnica  
