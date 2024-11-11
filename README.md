# Impacto de los Discursos de la FED

Este proyecto tiene como objetivo estudiar el impacto de los discursos de la Reserva Federal (FED) en el movimiento de diversas variables macroeconómicas a corto plazo.

### Estado del Proyecto: Activo

Actualmente, contamos con un **web scraper** funcional que extrae de manera automatizada los discursos de la FED. Hasta la fecha, se han recolectado **1,780 discursos**, los cuales incluyen su URL y fecha de publicación. Estos datos se almacenan en el archivo **Data_1996_Today_FED.csv**.

El modelo **FinBERT** es una variante de BERT (Bidirectional Encoder Representations from Transformers) entrenada específicamente para el análisis de sentimiento en el contexto financiero. Al aplicarlo a los discursos de la FED, FinBERT puede identificar el tono (positivo, negativo o neutral) de los mensajes y asignar probabilidades de pertenencia a cada categoría, por ejemplo: [0.10, 0.70, 0.20].

En la siguiente fase, se procederá a seleccionar y configurar el modelo que analizará las relaciones entre los discursos y las variables económicas.

Nota: Pensamos llamar al sistema "Aggregated Response Evaluation of Policy Announcements" (Evaluación de la respuesta agregada a los anuncios de política), o por sus siglas en inglés, AREPA.
