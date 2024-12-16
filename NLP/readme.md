# Desafíos de Procesamiento de Lenguaje Natural

Este repositorio contiene los archivos, códigos y análisis correspondientes a los cuatro desafíos realizados en la materia de **Procesamiento de Lenguaje Natural (PLN)**. Cada uno de estos desafíos aborda diferentes aspectos fundamentales del PLN, desde vectorización y clasificación hasta la construcción de un bot de preguntas y respuestas.

---

## Desafío 1: Vectorización y Clasificación con Naïve Bayes

### Consignas
1. **Vectorización de documentos:**
   - Selección de 5 documentos aleatorios y cálculo de la similaridad con el resto.
   - Análisis de los 5 documentos más similares y evaluación de la coherencia con el contenido y las etiquetas de clasificación.

2. **Clasificación con Naïve Bayes:**
   - Entrenamiento de modelos de clasificación para maximizar el **f1-score macro** en el conjunto de test.
   - Evaluación de los modelos **MultinomialNB** y **ComplementNB** con diferentes parámetros del vectorizador.

3. **Similaridad entre palabras:**
   - Transposición de la matriz documento-término para obtener una matriz término-documento.
   - Cálculo de la similaridad entre 5 palabras seleccionadas y sus 5 palabras más similares.


## Desafío 2: Embeddings con Gensim y Análisis de Analogías

### Consignas
- Creación de vectores de palabras usando **Gensim** con un nuevo dataset.
- Exploración de similitudes entre términos de interés.
- Pruebas de analogías y visualización de los embeddings resultantes.
- Extracción de conclusiones.

## Desafío 3: Generación de Secuencias

### Consignas
- Uso de un nuevo dataset para implementar estrategias de generación de secuencias, como:
  - **Greedy Search**
  - **Beam Search**
  - **Muestreo Aleatorio con Temperatura**

## Desafío 4: Construcción de un Bot de Preguntas y Respuestas (QA Bot)

### Consignas
- Creación de un **QA Bot** utilizando un dataset de preguntas y respuestas.
- Configuración recomendada:
  - **MAX_VOCAB_SIZE:** 8000
  - **max_length:** ~10
  - **Embeddings:** 300 (FastText)
  - **n_units:** 128
  - **LSTM Dropout:** 0.2
  - **Epochs:** 30-50

- Ejemplos de preguntas:
  - *Do you read?*
  - *Do you have any pet?*
  - *Where are you from?*



---


---

## Tecnologías Utilizadas

- **Python** (versión 3.8 o superior)
- **scikit-learn**
- **Gensim**
- **TensorFlow / Keras**
- **Matplotlib / Seaborn** para visualización

---


**Autor:** Fausto Juárez Yélamos

© 2024 - Todos los derechos reservados.
