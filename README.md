<img src="https://github.com/hernancontigiani/ceia_memorias_especializacion/raw/master/Figures/logoFIUBA.jpg" width="250" align="center">

CURSO DE ESPECIALIZACIÓN EN INTELIGENCIA ARTIFICIAL

**PROCESAMIENTO DE LENGUAJE NATURAL**

*Ing. Juan I. Munar, 11va Cohorte*

**CONTENIDO.** En el presente repositorio se encuentran los desafíos de la materia Procesamiento de Lenguaje Natural, dictada por el Dr. Rodrigo Cardenas Szigety entre octubre y diciembre del año 2023.

- **DESAFÍO 1: VECTORIZACIÓN**

	Obtención de diferentes representaciones de palabras, frases y frecuencias utilizando NumPy.

	[LINK D1](https://github.com/juanimunar/FIUBA_CEIA_PLN_MUNAR/blob/main/PLN__D1__VECTORIZACION_JIM.ipynb)

- **DESAFÍO 2: BOTS CONVERSACIONALES**

	Creación de dos BOTS sencillos:
	- BOT DNN + Spacy (PyTorch): BOT que funciona en base a un diccionario de posibles preguntas y respuestas y un modelo fully connected sencillo.
	- BOT TF-IDF + Similitud Coseno: a este BOT se le indica un documento a leer y se le introduce una pregunta relacionada, la respuesta se obtiene mediante similitud coseno.

	[LINK D2](https://github.com/juanimunar/FIUBA_CEIA_PLN_MUNAR/blob/main/PLN_D2_BOT_JIM.ipynb)

- **DESAFÍO 3: CUSTOM EMBEDDINGS CON GENSIM**

	A partir de un documento se crean embeddings de palabras basados en ese contexto. Se trabajó con los dos libros que componen el Martín Fierro de José Hernández para obtener embeddings de lengua gauchesca.

	[LINK D3](https://github.com/juanimunar/FIUBA_CEIA_PLN_MUNAR/blob/main/PLN_D3_EMBEDDINGS_JIM.ipynb)

- **DESAFÍO 4: PREDICCIÓN DE PALABRA**

	Se crean embeddings en el contexto de un documento utilizando Keras. Se utilizan los embeddings junto con layers LSTM para predecir la próxima palabra. 

	[LINK D4](https://github.com/juanimunar/FIUBA_CEIA_PLN_MUNAR/blob/main/PLN_D4_PREDICCION_JIM.ipynb)

- **DESAFÍO 5: SENTIMENT ANALYSIS**

	Se obtiene un modelo que, a partir de embeddings y capas LSTM, estima el puntaje que un comprador le asigna a un producto.
Se trata de un dataset desbalanceado, se evalúan alternativas de balanceo y el uso de dos tipos de embeddings, preentrenados o entrenados para el contexto.

	[LINK 5](https://github.com/juanimunar/FIUBA_CEIA_PLN_MUNAR/blob/main/PLN_D5_SENTIMENT_JIM.ipynb)

- **DESAFÍO 6: LSTM BOT QA**

	Se utilizan datos del challenge ConvAI2 para construir un BOT que responde preguntas del usuario. El BOT está basado en una arquitectura encoder-decoder.

	[LINK 6](https://github.com/juanimunar/FIUBA_CEIA_PLN_MUNAR/blob/main/PLN_D6_BOTQA_JIM.ipynb)
