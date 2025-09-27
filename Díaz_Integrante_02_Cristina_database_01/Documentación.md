# Documentación

## 1. Proceso de visualización  

Para la elaboración de la visualización se trabajó con un archivo inicial en formato Excel (`mujeres.xlsx`), el cual contenía información sobre atletas chilenas que participaron en los Juegos Panamericanos desde el 2003 al 2023 y marcas en competencias de atletismo.  

### Pasos realizados:
1. Investigación y recopilación de datos.
2. Creación de una base de datos en formato Excel.
3. Elaboración de un diccionario de datos, con descripción de variables, tipos de datos y notas de uso.

### Decisiones tomadas:
- Se optó por el formato **CSV** debido a su simplicidad, compatibilidad y facilidad de procesamiento en herramientas de análisis y visualización.  
- Se mantuvo la variable **Marca** en formato texto, aun cuando combina tiempos, distancias y pesos, con el objetivo de conservar la fidelidad del dato original.  
- Se documentaron observaciones y limitaciones de los datos en la ficha técnica.  

---

## 2. Base de datos utilizada  

- **Archivo:** `mujeres.csv`  
- **Procesamiento:** Conversión desde Excel → limpieza mínima (mantener variables principales).  
- **Motivo de selección:** Se centra en atletas chilenas que participaron en los Juegos Panamericanos y permite responder preguntas sobre su rendimiento en distintas disciplinas y años.  

---

## 3. Posibles preguntas de la visualización  

Algunas preguntas que la visualización puede responder:  
- ¿En qué disciplinas del atletismo destacan más las atletas chilenas?  
- ¿Cómo ha evolucionado el rendimiento de las atletas en el atletismo a lo largo de los años?  
- ¿Cómo varían las marcas según disciplina y año?  

---

## 4. Ficha técnica de la base de datos  

**Título:**  
Atletas Chilenas en los Juegos Panamericanos 

**Descripción:**  
Dataset con información sobre atletas chilenas en los Juegos Panamericanos, su participación en distintas disciplinas del atletismo y marcas obtenidas.  

**Cobertura temporal:**  
Años registrados en la columna **Año** (ejemplo: 2022–2023).  

**Cobertura geográfica:**  
Principalmente Chile.  

### Variables incluidas  


| Variable     | Descripción                          |
|--------------|--------------------------------------|
| **Nombre**   | Nombre completo de la atleta         |
| **Edad**     | Edad de la atleta                    |
| *Disciplina* | disciplina de atletismo              |
| **País**     | Nacionalidad de la atleta            |
| **Marca**    | Resultado deportivo alcanzado        |
| **Año**      | Año de la competencia                |

### Observaciones  
- La columna **Marca** combina diferentes unidades (segundos, kilos, metros). Puede requerir normalización si se quiere comparar entre disciplinas.  
- El dataset está diseñado para análisis exploratorios de rendimiento deportivo femenino en Chile.  

---

## 5. Archivos entregados  

-  `mujeres.csv` → Base de datos limpia en formato CSV  
- `README.md` → Documentación individual y ficha técnica  
