---
Fecha de creación: 2026-02-26 15:25
Fecha de Modificación: 2026-02-26 15:25
tags: 
Tema:
---


## 📚 Idea/Concepto 
La función de activación es una función matemática diferenciable que se aplica a la suma ponderada de entradas y sesgo de una neurona (𝑧 = 𝑤 ⋅ 𝑥 + 𝑏) para producir su salida (𝑎 = 𝑓(𝑧)). Su propósito es introducir no linealidad, evitando que una red profunda colapse en una transformación lineal. Estas funciones también actúan como mecanismos de filtrado o compresión de valores, y su elección impacta directamente el flujo de gradientes durante el entrenamiento. Por ejemplo, funciones como ReLU o GELU favorecen una mejor convergencia al mitigar problemas como el desvanecimiento de gradientes presente en funciones como la sigmoide. Además, su uso varía según la capa: en capas ocultas se emplean funciones como ReLU o GELU para modelar relaciones complejas, mientras que en la capa de salida se utilizan funciones como Softmax para generar distribuciones de probabilidad. En modelos modernos, GELU destaca por su suavidad y por permitir que incluso valores negativos contribuyan al aprendizaje.
## 🔗 Connections
- [[Redes Neuronales]] [[Arquitectura Transformer]] [[Alucinaciones]]
