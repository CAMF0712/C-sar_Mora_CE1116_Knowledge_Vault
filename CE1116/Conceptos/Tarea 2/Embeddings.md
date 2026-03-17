---
Fecha de creación: 2026-02-26 15:25
Fecha de Modificación: 2026-02-26 15:25
tags: 
Tema:
---


## 📚 Idea/Concepto 

Los embeddings son representaciones vectoriales densas que mapean datos discretos (como palabras u otros elementos) a puntos en un espacio vectorial continuo. Se implementan como una matriz de parámetros entrenables (lookup table), donde cada elemento tiene un vector asociado que se inicializa aleatoriamente y adquiere significado semántico mediante el entrenamiento del modelo (backpropagation). La relación entre los elementos se codifica a través de la proximidad y dirección de sus vectores, lo que permite capturar similitudes y realizar operaciones matemáticas como analogías vectoriales. La dimensionalidad de estos vectores es un hiperparámetro clave que afecta la capacidad representacional y el costo computacional. Además, los embeddings por sí solos no contienen información sobre el orden de los datos, por lo que requieren combinarse con codificaciones posicionales para representar secuencias. En su forma base, son estáticos, ya que asignan el mismo vector a un elemento independientemente del contexto.
## 🔗 Connections
- [[Tokenización]] [[Mecanismo de Atención]] [[Arquitectura Transformer]] [[Función de Activación]] [[User Story]]
