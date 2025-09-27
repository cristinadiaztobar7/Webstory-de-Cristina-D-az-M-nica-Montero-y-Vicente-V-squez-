# Atletas Chilenas en los Panamericanos
En esta sección se encuentra el diccionario de datos de las marcas de las atletas chilenas que participaron en los Juegos Panamericanos  

**Fuente:**  
Archivo original proporcionado en formato Excel, convertido a CSV para su uso y análisis.  

**Unidad de análisis:**  
Cada registro corresponde a una atleta en una competencia específica.  

**Cobertura temporal:**  
Años registrados en la columna **Año** (ejemplo: 2022–2023).  

**Cobertura geográfica:**  
Principalmente Chile.  

## 📑 Variables incluidas  

| Variable     | Descripción                          | Tipo                     | Ejemplo               |
|--------------|--------------------------------------|--------------------------|-----------------------|
| **Nombre**   | Nombre completo de la atleta         | Texto                    | María Pérez           |
| **Edad**     | Edad de la atleta                    | Entero                   | 23                    |
| **Disciplina** | Deporte en el que compite           | Texto (categórica)       | Atletismo             |
| **País**     | Nacionalidad de la atleta            | Texto (categórica)       | Chile                 |
| **Marca**    | Resultado deportivo alcanzado        | Texto / Numérico         | 12.45s (atletismo), 95kg (pesas) |
| **Año**      | Año de la competencia                | Entero                   | 2023                  |

## 📂 Formato del archivo  

- **Nombre del archivo:** `mujeres.csv`  
- **Formato:** CSV (valores separados por comas, codificación UTF-8)  

## ⚠️ Notas de uso  

- La variable **Marca** contiene valores heterogéneos (tiempos, pesos, distancias), por lo que puede requerir estandarización para análisis comparativos.  
- El dataset está diseñado para análisis exploratorios de rendimiento deportivo femenino en Chile.  