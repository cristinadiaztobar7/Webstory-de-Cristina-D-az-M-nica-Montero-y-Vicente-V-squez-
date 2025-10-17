## Entrega 03 – Visualización Individual
**Nombre:** Mónica Montero  
**Proyecto:** Rendimiento de atletas chilenos en los Juegos Panamericanos  
**Visualización 01 – Resultados masculinos (1951–2023)**  

---

### 1. Descripción general del trabajo  
Este trabajo forma parte del proyecto grupal sobre el rendimiento deportivo de Chile en los Juegos Panamericanos, enfocado exclusivamente en **atletismo**.  
En mi caso, analicé los resultados de **atletas chilenos hombres** desde **1951 hasta 2023**, con la idea de entender cómo ha cambiado su desempeño a lo largo del tiempo.  

Durante el proceso, trabajé con muchos archivos por separado y luego los fui limpiando y todavía no los he unificado por temas de tiempo, ya que debo ponerles los mismos nombres a las variables. 

---

### 2. Fuente y origen de los datos  
Los datos provienen del sitio oficial de **Athletics Panam**, donde están publicados los resultados de cada edición de los Juegos Panamericanos:  
🔗 [https://www.athleticspanam.com/ver2/resultados-juegos-panamericanos/](https://www.athleticspanam.com/ver2/resultados-juegos-panamericanos/)  

A partir de esos documentos, la profesora del curso generó archivos **CSV** que sirvieron como base para nuestro trabajo. Yo tomé esos archivos, seleccioné solo los resultados de **atletas chilenos hombres** y los fui limpiando año por año, realizando las correcciones correspondientes.   

En los casos donde faltaban datos (como fechas de nacimiento), preferí dejarlos vacíos para mantener la consistencia del archivo y no inventar información.  

---

### 3. Objetivo de la visualización  
La visualización busca responder una pregunta central:  
> **¿Cómo ha evolucionado el rendimiento de los atletas chilenos en el atletismo en los Juegos Panamericanos entre 1951 y 2023?** , pero para respoder esta pregunta todavía nos falta fusionar los resultados femeninos y masculinos. 

La idea es observar, a través del tiempo, si hubo mejoras, estancamientos o retrocesos, y detectar los años en que Chile logró mejores resultados. Esto también servirá después para comparar con otros factores, como el financiamiento o las políticas deportivas del país.  

---

### 4. Preguntas que puede responder esta visualización  
- ¿En qué periodos los atletas chilenos tuvieron un mejor rendimiento en atletismo masculino?  
- ¿Se pueden identificar etapas de crecimiento o caída en los resultados?  
- ¿Hubo algún año especialmente bueno?  
- ¿Existen décadas donde no se obtuvieron medallas en atletismo masculino?  

---

### 5. Proceso de trabajo  
1. Revisé los CSV originales entregados por la profesora.  
2. Filtré solo los resultados de deportistas chilenos hombres y eliminé las disciplinas que no correspondían a atletismo.  
3. Fui unificando la información año por año, corrigiendo nombres, fechas y formatos.
4. Generé documentos individuales con los CSV
5. Ahora me falta ponerlos todos en el mismo formato, es decir con las mismas variables. Como: (año, nombre_deportista, genero, fecha_nacimiento, disciplina, serie, marca, posicion, estado, fecha, lugar, instancia, integrantes)
   ```  
6. Verifiqué manualmente los nombres y las pruebas para evitar errores.  
7. Con la base final, hice una visualización en Python (usando Altair) que muestra la evolución del rendimiento a lo largo del tiempo.  

---

### 6. Resultado esperado  
El resultado es una visualización que muestra cómo ha sido el rendimiento histórico de los atletas chilenos en atletismo, desde los primeros Panamericanos en **Buenos Aires 1951** hasta **Santiago 2023**. La idea es ofrecer una mirada cuantitativa y contextual del rendimiento nacional, que luego se pueda complementar con el trabajo de mis compañeros sobre financiamiento y resultados femeninos.  

---

### 7. Distribución del trabajo en el equipo  
- **Mónica Montero:** procesamiento, limpieza y análisis de los resultados masculinos.  
- **Cristina Díaz:** análisis de los resultados femeninos.  
- **Vicente Vásquez:** recopilación de datos sobre presupuesto deportivo y programas de apoyo (como PRODDAR).  

Estas visualizaciones individuales se unirán en una **webstory final**, que mostrará cómo el contexto institucional y económico influye en el rendimiento deportivo de Chile a lo largo de los años.  







