# NLP-ECI2019
Trabajo final del curso de NLP dictado por germank durante la ECI2019
**Equipo**: Jorge Hané's Team.

**Integrantes**:

-Juan Musmarra

-Nicolás Ojea

-Matías Yerro

**Consigna**:
Uno de los datasets más famosos de Natural Language Inference es el SNLI. En esta tarea se debe responder, dadas dos frases A y B, si B es implicación de A ("entailment"), B es contradictorio con A ("contradiction") o si lo que enuncia B es neutral respecto de A ("neutral"). Se dice que A es la premisa y B es la hipótesis.
​
En **Gururangan et al., 2018** mostraron que este dataset tiene algunos sesgos, provocados por ejemplo por las heurísticas que tienen los humanos para generar estos pares de frases (A, B). Para ello, desarrollaron un modelo que aún sin observar la premisa A pudiera clasificar el par (A, B) en alguna de las tres clases del dataset.
​
En este trabajo práctico intentaremos predecir a qué clase pertenece cada una de las hipótesis sin observar la premisa. La idea es replicar los resultados publicados en Gururangan et al., 2018 y mejorarlos si es posible utilizando clasificadores más complejos.
​
Condiciones de entrega
Además de realizar al menos un envío replicando los resultados del paper antes mencionados, se deberá entregar el código del trabajo práctico junto a un breve informe que explique la idea del modelo implementado y una indicación de cómo ejecutar el programa si fuera necesaria. El trabajo podrá hacerse en grupos de hasta 3 personas.
