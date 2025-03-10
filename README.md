# modelo-lstm-tensorflow

Este repositorio contiene un ejemplo de un modelo **LSTM** (_Long Short-Term
Memory_) en [TensorFlow/Keras][1], para un Chatbot que será capaz de analizar
una frase de un cliente y clasificarla en una de las siguientes categorías:

- AYUDA
- OK
- SERVICIO_TECNICO

Los pasos que se han seguido son:

- Cargar un _dataset_ con los datos de entrenamiento.
- Construir un modelo de una red reuronal de tipo LSTM capaz de analizar texto.
- Entrenar la red neuronal.
- Evaluar la precisión del modelo.

## Contenido del repositorio

- [notebook](notebook/ejemplo_modelo_lstm.ipynb): Se trata de un notebook de
  [Google Colab][2] que contiene el código fuente del modelo LSTM en
  [TensorFlow/Keras][1] para [Python][3].
- [dataset](dataset/tsetdesordenado.txt): Contiene el dataset de entrenamiento
  desordenado.

## Créditos

Este ejemplo está basado en el código desarrollado por [José Antonio Torres
Ariaza](https://www.ual.es/persona/535053495455545772). Sólo se han modificado
algunos pequeños detalles del código original.

[1]: https://tensorflow.org
[2]: https://colab.research.google.com
[3]: https://www.python.org

## Referencias

- [Introducción a TensorFlow y Keras: Fundamentos y ejemplos](https://openwebinars.net/blog/tensorflow-keras-fundamentos/). OpenWebinars.
- [Introducción a las redes de memoria a corto-largo plazo (LSTM)](https://la.mathworks.com/discovery/lstm.html). MathWorks.
- [What Is a Recurrent Neural Network (RNN)?](https://la.mathworks.com/discovery/rnn.html). MathWorks.