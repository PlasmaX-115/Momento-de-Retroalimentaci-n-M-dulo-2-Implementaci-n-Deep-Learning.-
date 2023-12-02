# Momento de Retroalimentacion Modulo 2: Implementacion de un modelo de Deep Learning.

### Tweet Classification

El data set consiste de 10,000 tweets sobre desastres/accidentes. El objetivo es generar un modelo de Deep Learning capaz de identificar cuál de los tweets presenta un suceso real, y cuales no. En pocas palabras, se trata de un problema de NLP y clasificación binaria.

Se hará uso del modelo BERT para la clasificación.

El dataset está organizado de la siguiente manera:

Contienen:

- id
- keyword: Una palabra clave de ese tweet (Puede ser NaN).
- location: La ubicación desde donde se envió el (Puede ser NaN).
- text: El texto de un tweet.
- target: 1 si el tweet es un desastre real o 0 si es falso.
