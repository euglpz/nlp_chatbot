# TUIA - NLP 2023
# TRABAJO PRÁCTICO FINAL
El siguiente proyecto se basa en dos ejercicios:

En el primero se debe crear un chatbot experto en un tema a elección, usando la técnica RAG (Retrieval Augmented Generation).

En este caso el tema elegido es el **cine**, es decir, el chatbot va a poder responder a aquellas preguntas que sean relacionadas a la historia del cine, información de películas, directores, etc. 

Como fuentes de conocimiento se utilizarán las siguientes fuentes:
* Documentos de texto (PDF)
* Datos tabulares
* Base de datos de grafos
  
El sistema llevará a cabo una conversación en lenguaje español. El usuario podrá hacer preguntas, que el chatbot intentará responder a partir de datos de algunas de estas fuentes. El asistente podrá clasificar las preguntas, para saber qué fuentes de datos utiliza como contexto para generar la respuesta.

La ruta de nuestro chatbot será la siguiente:
![Ruta chatbot](https://raw.githubusercontent.com/euglpz/nlp_chatbot/master/archivos/ruta_chatbot.png)

---
Como segunda instancia, se realizará una investigación respecto al estado del arte de las aplicaciones actuales de agentes inteligentes usando modelos LLM libres, planteando una problemática a solucionar con un sistema multiagente.
Se desarrollará un informe con los resultados de la investigación y sus fuentes de información.

---
El proyecto está desarrollado por completo en una notebook de Google Colab. 

Para ejecutarlo se deberá acceder al archivo **tp_final_nlp.ipynb** e ir corriendo celda por celda.
