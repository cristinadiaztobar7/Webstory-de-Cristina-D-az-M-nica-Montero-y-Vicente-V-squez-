# Ficha Técnica de la Base de Datos

## Fuente de los datos
- Wikipedia: "Athletics at the Pan American Games" para cada edición consultada (2003, 2007, 2011, 2015, 2019 y 2023).  
  https://en.wikipedia.org/wiki/Athletics_at_the_2003_Pan_American_Games  
- World Athletics: resultados oficiales de cada edición.  
  Ejemplo 2023: https://worldathletics.org/competition/calendar-results/results/7144863?eventId=10229630&gender=M  
- La Historia del Atletismo de El Salvador: resultados históricos de los Juegos Panamericanos.  
  https://atletismoelsalvador.org/resultados-de-juegos/resultados-juegos-panamericanos/

## Metodología de construcción
- Se recopilaron datos de todas las ediciones entre 2003 y 2023 de fuentes oficiales y confiables.  
- Se filtraron los registros correspondientes únicamente a deportistas chilenos.  
- La limpieza fue manual, incluyendo: corrección de nombres, estandarización de fechas, marcas y posiciones, eliminación de duplicados y registros no relevantes.  
- Se organizaron las variables de manera que faciliten responder la hipótesis y preguntas de investigación.

## Alcance de los datos
- Cobertura: atletas chilenos en los Juegos Panamericanos de 2003, 2007, 2011, 2015, 2019 y 2023.  
- Incluye todas las disciplinas y pruebas en las que participaron atletas chilenos.  
- Permite analizar medallas, participación por disciplina, recurrencia de atletas, edad y desempeño histórico.

## Característica de los datos
- Tipo de datos: mixto (numéricos, texto, fechas).  
- Formato final: CSV limpio, sin registros duplicados ni datos faltantes críticos.  
- Preparado para análisis estadístico, tablas dinámicas y visualizaciones.  
- Cada registro corresponde a un atleta en una prueba específica de una edición determinada.

## Variables incorporadas

| Variable               | Descripción                                                                 |
|------------------------|----------------------------------------------------------------------------|
| Año                    | Año de la edición de los Juegos Panamericanos                                |
| Nombre                 | Nombre completo del atleta                                                 |
| Disciplina             | Nombre de la disciplina                                                    |
| Tipo de prueba         | Clasificación de la prueba (pista, campo, relevos, etc.)                  |
| Unidad de Medida       | Unidad en la que se registra la marca (segundos, metros, etc.)            |
| Marca                  | Resultado obtenido por el atleta                                           |
| Posición               | Posición final en la prueba                                                |
| Total de competidores  | Número total de atletas que compitieron en la prueba                       |
| Récord (SB, PB)        | Indica si la marca corresponde a su mejor marca de la temporada (SB) o personal (PB) |
| Fecha de nacimiento     | Fecha de nacimiento del atleta                                             |
| Edad                   | Edad del atleta durante la edición de los Juegos                            |
| Instancia              | Etapa de la prueba (clasificación, semifinal, final)                       |

## Otras observaciones
- La base incluye únicamente atletas chilenos.  
- Se utilizaron varias fuentes para completar información histórica y validar resultados.  
- El orden de los registros sigue la cronología de las ediciones y la estructura de la fuente oficial siempre que fue posible.  
- Las variables fueron definidas para permitir análisis de desempeño, tendencias históricas y comparaciones entre atletas y disciplinas.

