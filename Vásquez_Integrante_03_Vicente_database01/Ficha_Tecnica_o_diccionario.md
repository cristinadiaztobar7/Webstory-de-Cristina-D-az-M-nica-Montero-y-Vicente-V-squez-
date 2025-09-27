# Ficha Técnica Base de datos

## Fuente de los datos
- Asociacón Panamericana de Atletismo, Resultados Juegos Panamericanos de las ediciones 2003, 2007, 2011, 2015, 2019 y 2023.

  https://www.athleticspanam.com/ver2/resultados-juegos-panamericanos/  

- Juegos Panam 2023 Santiago, Schedule Event. Organización y resultados de cada una de las competiciones realizadas con fecha y hora.

  https://results-santiago2023.org/#/discipline/ATH/schedule/by-event/M.100M-------------- 

- Fuente: Fuente: Atletismo El Salvador, “Resultados Juegos Panamericanos” donde podemos ver el resultado de cada una competencias de atletismo realizadas en las ediciones entre 2003 y 2023.

  https://atletismoelsalvador.org/resultados-de-juegos/resultados-juegos-panamericanos/ 

## Metodología de construcción
- Los datos fueron recopilados de las fuentes oficiales que participaron de la organización de los eventos entre 2003 y 2023
- La limpieza de los datos fue de forma manual, por lo que cualquier dato que está inscrito en la base de datos está estandarizado en base a las necesidades del proyecto, eliminando datos no relevantes.

- Se realizaron tablas con variables que nos permiten identificar solamente a deportistas del género femenino, que forman parte del equipo chileno y que han participado de competencias de atletismo.

## Alcance de los datos
- Cobertura: atletas chilenas participantes de los Juegos Panamericanos de 2003, 2007, 2011, 2015, 2019 y 2023.
- Son tomadas en cuenta todas las disciplinas del atletismo en los que hayan participado deportistas chilenas.  
- Incluye el análisis de cada deportista, año de participación, sede de los Juegos Panamericanos, categoría a la que pertenecen, disciplina, fase en la que participaron, resultado o marca de cada participación, puesto que ocuparon en la clasificación y si obtuvieron alguna medalla.

## Característica de los datos
- Tipo de datos: mixto (numéricos, texto, fechas).  
- Formato final: CSV limpio, sin registros duplicados ni datos faltantes críticos.  
- Preparado para análisis estadístico, tablas dinámicas y visualizaciones.  
- Cada registro corresponde a un atleta en una prueba específica de una edición determinada.

## Variables incorporadas

| Variable               | Descripción                                                                 |
|------------------------|----------------------------------------------------------------------------|
| Año                    | Año de la edición de los Juegos Panamericanos                                |
| País                 | País donde se realizaron los Juegos Panamericanos                                               |
| Categoría            | Géneros que compiten en aquella categoría                                             |
| Nombre del atleta        | Nombre de la deportista              |
| Disciplina      | Nombre de la disciplina    |
| Fase                  | Etapa de cada competencia                                |
| Marca/resultado              | Marca realizada por la atleta                           |
| Puesto  | Posición final de la clasificación que ocupa la deportista                     |
| Medalla        | Indica si la deportista ganó una medalla                 |

## Otras observaciones
- La base solamente toma a atletas femeninas chilenas.
- La información fue contrastada entre diversas fuentes oficiales y confiables 
- Todas las variables permiten identificar cuantas veces participó cada atleta entre 2003 y 2023, además de saber cuántas disciplinas realizó y sus mejores marcas en cada edición.