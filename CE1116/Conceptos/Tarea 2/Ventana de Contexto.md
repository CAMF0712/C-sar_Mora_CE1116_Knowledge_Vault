---
Fecha de creación: 2026-02-26 15:25
Fecha de Modificación: 2026-02-26 15:25
tags: 
Tema:
---


## 📚 Idea/Concepto 

La ventana de contexto es el límite máximo de tokens que un modelo puede procesar simultáneamente mediante el mecanismo de self-attention, funcionando como una memoria de trabajo operativa. Este límite define cuánta información puede ser analizada en una sola operación y está determinado por el diseño del modelo. El tamaño de la ventana condiciona la capacidad del modelo para capturar dependencias complejas en secuencias largas, y su costo computacional crece de forma cuadrática (𝑂(𝑛2)) con respecto al número de tokens. Cuando se excede este límite, el modelo debe truncar la entrada o generar respuestas con información incompleta, lo que puede provocar errores o alucinaciones. Además, la ventana de contexto se comparte entre todos los elementos de la interacción (instrucciones, datos de entrada y respuesta generada), y su rendimiento no es uniforme: el modelo tiende a priorizar la información al inicio y al final de la secuencia, fenómeno conocido como “lost in the middle”.
## 🔗 Connections
- [[Tokenización]] [[Mecanismo de Atención]] [[Alucinaciones]] [[Requerimientos No Funcionales]]
