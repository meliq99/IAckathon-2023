# Modelo de red neuronal LSTM para la predicción del volumen de procesos en la categoría de Menor Cuantía 2018 - 2023 

Este repositorio contiene un modelo de red neuronal LSTM (Long Short-Term Memory) desarrollado para la predicción del volumen de procesos en la categoría de menor cuantía. La elección de este modelo se basa en su capacidad para predecir series temporales, lo que lo convierte en una herramienta poderosa para anticipar el número de procesos que se llevarán a cabo el mes siguiente y comprender su comportamiento a lo largo del tiempo.

<img src="https://github.com/meliq99/IAckathon-2023/blob/master/im%C3%A1genes/menorcuantia.png">

# Contexto del Proyecto

Los datos utilizados en este proyecto fueron recopilados de la categoría de menor cuantía desde el año 2018 hasta el 14 de septiembre de 2023 desde la plataforma [Datos Abiertos de contratación pública del Ecuador en OCDS](https://datosabiertos.compraspublicas.gob.ec/PLATAFORMA/datos-abiertos). 

## Objetivo del Proyecto 
El objetivo principal de este proyecto es desarrollar un modelo de predicción preciso que pueda ayudar en la planificación y toma de decisiones relacionadas con los procesos de menor cuantía. El modelo de red neuronal LSTM se entrena utilizando estos datos históricos y se evalúa su capacidad para pronosticar el volumen futuro de procesos.

## Metodología 
* **Extracción de datos:** Se seleccionó los datos de la categoría Menor Cuantía de  los años 2018 - 2023, en formato CSV. 
* **Selección de datos:** Se extrajo información relevante de los datos, específicamente la fecha de inicio del período de licitación **(tenderPeriod_startDate)** del apartado de **Tender**. 
* **Pre-proceso de datos:** Existieron días en donde no se encontraron procesos de licitación debido a esto se procedió a remplazar la data faltante por 0. Luego, estas fechas se utilizaron para calcular la cantidad de procesos que se realizan diariamente, que denominamos **'Frequency'**.
* **Creación del modelo:** Se procedió a la creación del modelo.
 

Siéntase libre de explorar el código y los resultados en este repositorio para obtener más detalles sobre el modelo, como la división de los datos para validación y testeo, la afinación de hiperparámetros, la metrica usada para medir la precisión del modelo, y sus aplicaciones en la categoría de menor cuantía, en el siguiente[COLAB](https://colab.research.google.com/drive/1iufFQNTk_LX2AAyes_-0kqLvEAVvjtDJ?usp=sharing).



## Visualización de las Predicciones

Se adaptaron los resultados para poder visualizarlos desde el 2 de Mayo del 2023 hasta el 27 de Agosto del 2023. Mostrando una predicción de todo el mes de Agosto del 2023.
Para explorar en detalle los datos procesados y las predicciones generadas por nuestro modelo, le invitamos a visitar la plataforma de visualización en Tableau llamada "Predicciones de Contratos Menor Cuantía". Aquí encontrará un gráfico interactivo que proporcionan una comprensión completa del volumen de procesos y las predicciones asociadas.

Por favor, acceda a nuestra [visualización en Tableau](https://public.tableau.com/views/MenorCuantaEcuador2018-2023/Dashboard2?:language=es-ES&:display_count=n&:origin=viz_share_link) para analizar de manera más profunda y personalizada las predicciones y los datos históricos. Este recurso le permitirá tomar decisiones informadas y planificar estratégicamente en el contexto de la categoría de MENOR CUANTIA.

<img src="https://github.com/meliq99/IAckathon-2023/blob/master/im%C3%A1genes/datos.png">

# Explicación del Proyecto (video)
Podra encontrar la explicación del código y de la visualización de la gráfica en el siguiente     [VIDEO](https://drive.google.com/drive/folders/12gipx5SR8YG5cNOTxBEPkWRXFZAyQQCh?usp=sharing)

# AUTORES
* [Melissa Marisol Quiñonez Londoño](https://www.linkedin.com/in/melissa-qui%C3%B1onez-0015041a1/) (melissa.quinonez@yachaytech.edu.ec)
* [Escobar Caicedo Sergy Joel](https://www.linkedin.com/in/sergy-escobar-626588293) (sergy.escobar@yachaytech.edu.ec)
* [Paredes Benavides Jimmy Gerardo](https://www.linkedin.com/in/jimmy-paredes-43258a293)  (jimy.paredes@yachaytech.edu.ec)
