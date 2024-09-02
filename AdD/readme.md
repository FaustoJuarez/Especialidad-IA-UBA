# Trabajo Práctico Integrador: Análisis de Datos con Spotify

## 1. Introducción y Motivación

El objetivo de este trabajo práctico es realizar un análisis completo de un set de datos. En particular, hemos elegido el dataset de canciones de Spotify para explorar y responder preguntas clave relacionadas con la predicción del gusto musical de los usuarios.

### 1.1 Dataset de Spotify

Este dataset contiene información sobre distintas canciones en Spotify. El objetivo principal es estimar si un tema nuevo será del gusto de una persona con una playlist activa. La variable `label` será nuestra variable de salida a analizar.

## 2. Análisis Exploratorio Inicial

1. **Visualización de Datos**  
   Visualizar las primeras filas del dataset para obtener una vista preliminar de los datos.

2. **Resumen de 5 Números**  
   Realizar un resumen estadístico básico (mínimo, primer cuartil, mediana, tercer cuartil, máximo) para comprender la distribución de las variables numéricas.

3. **Tipos de Datos**  
   Identificar y clasificar los tipos de datos (categóricos, ordinales, numéricos) presentes en el dataset. Evaluar si cada variable es informativa para un problema de clasificación, identificando las variables de entrada y salida.

4. **Análisis por Tipo de Variable**
   - **Numéricas**: Analizar la distribución de los datos.
   - **Categóricas**: Evaluar la cardinalidad y representación de cada categoría.
   - **Compuestas**: Considerar cómo pueden tratarse estas variables para su uso en el modelo.

5. **Balance de Clases**  
   Verificar si las clases en la variable de salida están balanceadas. En caso de desbalance, considerar técnicas de codificación apropiadas.

## 3. Limpieza y Preparación de Datos / Ingeniería de Features

1. **Datos Faltantes**  
   Identificar la cantidad de observaciones y valores faltantes por variable. Proponer y ensayar distintas técnicas de imputación, analizando sus resultados.

2. **Codificación de Variables**  
   Elegir una técnica de codificación para cada variable en función del análisis previo. Ensayar y comparar distintas técnicas, considerando el tipo de clasificador a utilizar.

3. **Relaciones entre Variables de Entrada**  
   Analizar las relaciones entre las variables de entrada y determinar cuáles son las más importantes. Utilizar al menos dos técnicas para evaluar la importancia de cada variable.

## 4. Entrenamiento de Modelos (Opcional)

1. **Selección de Modelos**  
   Definir una lista de modelos candidatos para entrenar. Probar distintas combinaciones de técnicas de procesamiento de datos (imputación, selección de variables, codificación, etc.).

2. **Separación de Datos**  
   Particionar el dataset en conjuntos de entrenamiento y validación para evaluar los modelos.

3. **Evaluación de Resultados**  
   Evaluar cómo cada preparación de datos afecta el desempeño de los modelos. Extraer conclusiones sobre las técnicas más efectivas.

## 5. Presentación de Resultados

El trabajo final se presentará en un bloque de tiempo máximo de 15 minutos por grupo. Se recomienda también entregar un informe de varianza corto para guiar el desarrollo del proyecto.

---

Este README proporciona una guía clara para abordar el análisis del dataset de Spotify, organizando las tareas en una secuencia lógica que facilita el desarrollo y la presentación del trabajo.
