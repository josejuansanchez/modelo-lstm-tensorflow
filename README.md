# modelo-lstm-tensorflow

Este repositorio contiene un ejemplo de un modelo **LSTM** (_Long Short-Term
Memory_) para un Chatbot que será capaz de analizar una frase de un cliente y
clasificarla en una de las siguientes categorías:

- AYUDA
- OK
- SERVICIO_TECNICO

Los pasos que vamos a seguir son:

- Cargar un dataset con los datos de entrenamiento. En nuestro caso será un archivo de texto.
- Construir un modelo de una red reuronal de tipo LSTM capaz de analizar texto.
- Entrenar la red neuronal.
- Evaluar la precisión del modelo.

## Créditos

Este ejemplo está basado en el código desarrollado por [José Antonio Torres
Ariaza](https://www.ual.es/persona/535053495455545772), sólo se han modificado
algunos pequeños detalles.