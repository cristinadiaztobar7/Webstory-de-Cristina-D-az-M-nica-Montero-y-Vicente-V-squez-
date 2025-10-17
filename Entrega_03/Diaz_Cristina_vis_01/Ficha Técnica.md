# Ficha Técnica

**Nombre del dataset:** Atletismo femenino chileno 1951–2023  
**Fuente(s):** Comité Olímpico de Chile (COCh), Panam Sports y registros de World Athletics (WA Points). Este Dataset también se deriva de una entrega anterior (Ver Entrega 2)
**Cobertura temporal:** 1951–2023  
**Cobertura geográfica:** Chile / Juegos Panamericanos  
**Unidad de análisis:** Atleta por disciplina y año  
**Periodicidad:** Cuatrienal (cada edición panamericana)  
**Última actualización:** 2023-11-15

Estos datos en general estaban hechos para centrarse solo en el desempeño del atletismo femenino de los Juegos Panamericanos, sin embargo en medio de la limpieza de datos hubieron ligeras modificaciones nacidas de la practicidad y la necesidad de comparar datos de otros países.
También hubieron complicaciones con las variables, pero se resolvieron dentro del colab, en especial por la variable "año", la cual era interpretada como "anio" debido a asuntos de corrección dentro de la plataforma. Sin embargo, se pudo una limpieza completa.
Las variables principales son "Discipina", "Nombre de la Atleta", "Marca", "Medalla" y "Puesto".

## Transformaciones
Dentro de colab, realicé una serie de cambios y transformaciones en un esfuerzo de optimizar la limpieza de los datos, en especial debido a los setenta años que abarca.
- Eliminé duplicados por atleta y año.
- los nombres de disciplinas fueron normalizados dentro de lo posible.
- Pasé los datos por Pandas y Altair para automatizar el proceso y tener una buena visualización de los datos.

## Limitaciones y advertencias
- Los registros previos a 1975 pueden tener errores de cronometraje manual.
- No todos los años incluyen la misma cantidad de disciplinas ni de participantes.
- No hay profundización en apoyos gubernamentales.
- Hay errores de tipeo casi imposibles de limpiar (Los CSV de años anteriores a los 70 solo ponen "Men" en la categoría de género.
- Representatividad limitada al nivel panamericano (no incluye campeonatos sudamericanos).
- los Datos entregados no reflejan continuidad necesariamente.
