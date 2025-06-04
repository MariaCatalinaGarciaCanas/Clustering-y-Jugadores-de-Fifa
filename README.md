Clustering de Jugadores de FIFA 18
¡Bienvenido a este proyecto de análisis y clustering de jugadores del popular videojuego FIFA 18! ⚽🎮

Descripción
En este proyecto nos sumergimos en el universo de FIFA 18 para explorar un dataset con información detallada de miles de jugadores de las ligas más importantes del mundo. Cada jugador tiene un perfil extenso con características como edad, nacionalidad, club, valor de mercado, salario, y atributos técnicos como agilidad, tiros libres, aceleración, equilibrio y posiciones en el campo.

El objetivo principal es aplicar técnicas de clustering para descubrir grupos o segmentos naturales entre los jugadores y entender qué características los agrupan. Así podemos responder preguntas como:

¿Existen grupos claros de jugadores según su estilo de juego o atributos?

¿Qué diferencia a un jugador defensor de un delantero a nivel de atributos técnicos?

¿Cómo se agrupan los jugadores según su valor y desempeño?

Dataset
El dataset utilizado proviene de FIFA 18 y contiene más de 17,000 registros con aproximadamente 75 columnas por jugador. Algunas de las variables más importantes incluyen:

Name: Nombre del jugador

Age: Edad

Nationality: País de origen

Club: Equipo en el que juega

Value: Precio de mercado (convertido a valores numéricos)

Wage: Salario semanal

Atributos técnicos: Aceleración, agilidad, control de balón, precisión en tiros libres, etc.

Posiciones: CAM, CB, CDM, CF, CM, y más

Proceso
Limpieza y preparación de datos

Eliminación de columnas irrelevantes (como URLs de fotos o logos).

Conversión de valores monetarios de formato texto a numérico (millones y miles).

Eliminación de jugadores con valor 0 para evitar ruido en el análisis.

Selección de características

Selección de variables numéricas relevantes para clustering, enfocándonos en atributos técnicos y físicos.

Análisis exploratorio

Visualización y descripción estadística para entender la distribución de los datos.

Aplicación de clustering

Escalamiento de datos con StandardScaler.

Uso de PCA para reducción de dimensionalidad y visualización.

Uso de K-Means para agrupar jugadores en clusters basados en sus atributos.

Interpretación

Análisis de cada cluster para identificar qué los caracteriza.

Interpretación en términos de posiciones, valor de mercado y características técnicas.

Resultados esperados
Identificación de grupos diferenciados de jugadores (por ejemplo, defensores con alta resistencia y fuerza, delanteros con alta precisión y velocidad, etc.).

Visualizaciones que faciliten la interpretación y presentación de los clusters.

Insights útiles para scouts, entrenadores, o analistas de fútbol para entender mejor las características que definen distintos tipos de jugadores.

Tecnologías y librerías usadas
Python 3.x

pandas, numpy (manejo y limpieza de datos)

seaborn, matplotlib (visualización)

scikit-learn (preprocesamiento, PCA, K-Means clustering)
