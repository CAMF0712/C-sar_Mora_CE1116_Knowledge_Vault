---
Fecha de creación: 2026-02-26 15:25
Fecha de Modificación: 2026-02-26 15:25
tags: 
Tema:
---


## 📚 Idea/Concepto 

La arquitectura Transformer es un modelo de redes neuronales diseñado para procesar secuencias mediante mecanismos de atención que capturan dependencias globales entre los elementos, independientemente de su posición. A diferencia de modelos como RNN o CNN, elimina la recurrencia y las convoluciones, lo que permite procesar secuencias completas en paralelo durante el entrenamiento, mejorando la eficiencia y escalabilidad. El modelo se compone de bloques que incluyen mecanismos de self attention basados en vectores de Query, Key y Value, junto con Multi-head Attention para aprender múltiples relaciones simultáneamente. Además, incorpora redes Feed Forward, conexiones residuales y Layer Normalization para estabilizar el entrenamiento en arquitecturas profundas. Dado que no tiene una noción inherente de orden, utiliza codificación posicional para representar la secuencia. Finalmente, en tareas de generación de texto, los vectores resultantes se transforman mediante una capa lineal y una función Softmax para producir una distribución de probabilidad sobre el vocabulario, permitiendo la generación autorregresiva de tokens.
## 🔗 Connections
- [[Mecanismo de Atención]] [[Embeddings]] [[Ventana de Contexto]] [[Alucinaciones]] [[Requerimientos No Funcionales]]
