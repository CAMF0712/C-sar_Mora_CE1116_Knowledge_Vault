---
Fecha de creación: 2026-02-26 15:25
Fecha de Modificación: 2026-02-26 15:25
tags: 
Tema:
---


## 📚 Idea/Concepto 

El mecanismo de atención es una operación matemática que transforma embeddings en representaciones contextuales enriquecidas, permitiendo capturar dependencias entre elementos de una secuencia sin importar su distancia. Este proceso se basa en el mapeo de vectores Query, Key y Value, los cuales se obtienen mediante proyecciones lineales aprendidas a partir de los embeddings originales utilizando matrices de pesos (𝑊𝑄,𝑊𝐾,𝑊𝑉). La relevancia entre elementos se calcula mediante el producto punto entre Query y Key, el cual se escala por un factor 1/√𝑑𝑘 para estabilizar los valores antes de aplicar una normalización (Softmax). Estos pesos se utilizan para calcular una suma ponderada de los vectores Value, generando un vector de contexto que integra información relevante de toda la secuencia. Este mecanismo permite un procesamiento paralelo eficiente al eliminar la dependencia de estructuras recurrentes.
## 🔗 Connections
- [[Arquitectura Transformer]] [[Embeddings]] [[Ventana de Contexto]] [[Requerimientos No Funcionales]]
