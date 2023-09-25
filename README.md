# Modelo de red neuronal LSTM para la predicción del volumen de procesos en la categoria de Menor Cuantía (IAckathon-2023)

Este repositorio contiene un modelo de red neuronal LSTM (Long Short-Term Memory) desarrollado para la predicción del volumen de procesos en la categoría de menor cuantía. La elección de este modelo se basa en su capacidad para predecir series temporales, lo que lo convierte en una herramienta poderosa para anticipar el número de procesos que se llevarán a cabo el mes siguiente y comprender su comportamiento a lo largo del tiempo.

<img src="https://github.com/meliq99/IAckathon-2023/blob/master/im%C3%A1genes/menorcuantia.png">
## Contexto del Proyecto

Los datos utilizados en este proyecto fueron recopilados de la categoría de menor cuantía desde el año 2018 hasta el 14 de septiembre de 2023 desde la plataforma [Datos Abiertos de contratación pública del Ecuador en OCDS](https://datosabiertos.compraspublicas.gob.ec/PLATAFORMA/datos-abiertos). Se extrajo información relevante de los datos, específicamente la fecha de inicio del período de licitación **(tenderPeriod_startDate)** del apartado de **Tender**. Estas fechas se utilizaron para calcular la cantidad de procesos que se realizan diariamente, que denominamos **'Frequency'**.

El objetivo principal de este proyecto es desarrollar un modelo de predicción preciso que pueda ayudar en la planificación y toma de decisiones relacionadas con los procesos de menor cuantía. El modelo de red neuronal LSTM se entrena utilizando estos datos históricos y se evalúa su capacidad para pronosticar el volumen futuro de procesos.

Siéntase libre de explorar el código y los resultados en este repositorio para obtener más detalles sobre el modelo y sus aplicaciones en la categoría de menor cuantía, en el siguiente enlace [COLAB](https://colab.research.google.com/drive/1iufFQNTk_LX2AAyes_-0kqLvEAVvjtDJ?usp=sharing).



## Visualización de las Predicciones

Para explorar en detalle los datos procesados y las predicciones generadas por nuestro modelo, le invitamos a visitar la plataforma de visualización en Tableau llamada "Predicciones de Contratos Menor Cuantía". Aquí encontrará un gráfico interactivo que proporcionan una comprensión completa del volumen de procesos y las predicciones asociadas.

Por favor, acceda a nuestra [visualización en Tableau](https://public.tableau.com/views/MenorCuantaEcuador2018-2023/Dashboard2?:language=es-ES&:display_count=n&:origin=viz_share_link) para analizar de manera más profunda y personalizada las predicciones y los datos históricos. Este recurso le permitirá tomar decisiones informadas y planificar estratégicamente en el contexto de la categoría de MENOR CUANTIA.

