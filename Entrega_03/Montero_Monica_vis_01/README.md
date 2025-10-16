# Entrega 03 – Visualización Individual

**Nombre:** Mónica Montero  
**Proyecto:** Rendimiento de atletas chilenos en los Juegos Panamericanos  
**Visualización 01 – Resultados masculinos (1951–2023)**

---

## 1. Descripción general del trabajo

Esta visualización forma parte del proyecto grupal de análisis del rendimiento deportivo de Chile en los Juegos Panamericanos, enfocado exclusivamente en atletismo. En mi caso, trabajé con los resultados de atletas **chilenos hombres** desde **1951 hasta 2023**, buscando visualizar el desempeño a lo largo del tiempo en términos de medallas obtenidas por edición.

---

## 2. Fuente y origen de los datos

Los datos provienen de la página web oficial de Athletics Panam:  
 [https://www.athleticspanam.com/ver2/resultados-juegos-panamericanos/](https://www.athleticspanam.com/ver2/resultados-juegos-panamericanos/)

En este sitio se encuentran los archivos PDF con los resultados de cada edición de los Juegos Panamericanos. A partir de estos documentos, la profesora del curso generó archivos **CSV compilados** para facilitar el trabajo de limpieza y análisis. Utilicé dichos archivos como base, enfocándome en los resultados de deportistas **masculinos chilenos**.

---

## 3. Objetivo de la visualización

La visualización busca responder a la siguiente pregunta:  
**¿Cómo ha evolucionado el rendimiento de los atletas chilenos hombres en atletismo en los Juegos Panamericanos entre 1951 y 2023, medido a través del número de medallas obtenidas?**

Este gráfico permite observar posibles mejoras, estancamientos o retrocesos a lo largo del tiempo, y servirá como insumo para contrastar con otras variables como el financiamiento estatal o los programas de apoyo institucional.

---

## 4. Preguntas que puede responder esta visualización

- ¿En qué periodos hubo un mejor desempeño de atletas chilenos en atletismo masculino?
- ¿Existen ciclos o tendencias claras de mejora o retroceso?
- ¿Hubo un rendimiento especialmente alto en alguna edición puntual (por ejemplo, Santiago 2023)?
- ¿Hay décadas donde Chile no logró medallas en atletismo masculino?

---

## 5. Proceso de trabajo

- Se revisaron los CSV base proporcionados por la profesora.
- Se filtraron únicamente los resultados de **deportistas chilenos hombres**.
- Se estandarizaron nombres de columnas, fechas y disciplinas.
- Se construyó una tabla resumen con el número total de medallas obtenidas por año.
- Se diseñó una visualización de tipo **línea temporal** con la librería Altair (Python).
- Se exportaron los resultados en formato `.html` y `.jpg` para su inclusión en la webstory del proyecto.

---

## 6. Resultado esperado

Esta visualización entrega una perspectiva cuantitativa de la evolución histórica del rendimiento de los atletas chilenos hombres en atletismo, a través de los Juegos Panamericanos entre 1951 y 2023. El objetivo es facilitar el análisis de posibles patrones de mejora, estancamiento o retroceso en los resultados obtenidos.

Dentro del equipo, la carga de trabajo fue distribuida de la siguiente forma:
- **Mónica Montero (yo):** procesamiento y análisis de los datos correspondientes a **deportistas hombres**.
- **Cristina Díaz:** análisis de los resultados de **deportistas mujeres**.
- **Vicente Vásquez:** recopilación y visualización de información sobre **presupuesto público en alto rendimiento deportivo** y la cantidad de deportistas beneficiados por la beca PRODDAR.

Estas visualizaciones individuales permitirán construir una narrativa conjunta en la webstory final, cruzando variables de rendimiento con factores institucionales como el financiamiento y las políticas de apoyo al deporte.








