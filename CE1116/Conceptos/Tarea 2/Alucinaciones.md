---
Fecha de creación: 2026-02-26 15:25
Fecha de Modificación: 2026-02-26 15:25
tags: 
Tema:
---


## 📚 Idea/Concepto 

Las alucinaciones en modelos de inteligencia artificial son respuestas generadas que, aunque coherentes en forma, son incorrectas desde el punto de vista factual. Este fenómeno surge de la naturaleza probabilística del modelo, que predice el siguiente token basándose en distribuciones estadísticas aprendidas, en lugar de acceder a hechos verificables. Se pueden entender como una confabulación estadística derivada de la falta de grounding, donde la información no se consulta explícitamente, sino que emerge de patrones distribuidos en los pesos del modelo. En arquitecturas autorregresivas, este problema se amplifica, ya que cada token generado se incorpora al contexto y condiciona los siguientes, propagando errores si se introduce información incorrecta. Además, pequeñas variaciones en los valores de salida (logits) pueden llevar a seleccionar tokens incorrectos, afectando toda la secuencia posterior. Factores como la calidad del prompt y las limitaciones del contexto también influyen en la aparición de este fenómeno.
## 🔗 Connections
- [[Ventana de Contexto]] [[Arquitectura Transformer]] [[Embeddings]] [[Tokenización]] [[Pruebas Funcionales]] [[Definition of Done (DoD)]] [[Stakeholder]]
