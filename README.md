Para procesamiento de datos BigData, se presentan 2 alternativas con 2 frameworks ampliamente utilizados:

Hadoop MapReduce: (Se está reemplazando progresivamente por frameworks mas performantes como Spark). Para evitar el uso de clusters reales y costosos, se utiliza un emulador de MapReduce 
desarrollado por la cátedra del postgrado de Inteligencia de datos en entornos Big Data (Materia: Conceptos y aplicaciones en BigData)
En este proyecto se realiza el cálculo de TF-IDF para un término ingresado por teclado en un conjunto Big Data de reviews de películas

Spark: (Apache Spark es un framework para computación distribuída que prioriza el trabajo en memoria (en general mas performante que MapReduce para muchas tareas)
En este proyecto se realiza un algoritmo de clustering para una serie de datos vectorizados numéricos que representan muestras de sangre, se utiliza K-Means de manera manual (exponiendo 
también la lógica que implica el algoritmo de K-Means, una alternativa mas sencilla sería utilizar las herramientas de Machine Learning que provee la librería MLlib de Spark, instanciando
un modelo de KMeans, pero el objetivo es centrarse en el procesamiento de transacciones y acciones en Spark). 

Autor: Diego Fernando Tarrío (Licenciado en Informática)
Cursando maestría en Inteligencia de datos en entorno Big Data U.N.L.P.
2024
