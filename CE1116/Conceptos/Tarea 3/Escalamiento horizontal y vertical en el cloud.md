---
Fecha de creación: 2026-02-26 15:25
Fecha de Modificación: 2026-02-26 15:25
tags: 
Tema:
---


## 📚 Idea/Concepto 

El escalamiento en el cloud es la capacidad de ajustar recursos computacionales para responder a la demanda. El escalamiento vertical consiste en aumentar la capacidad de una instancia (CPU, RAM), pero está limitado por el hardware disponible y, en muchos casos, implica tiempo de inactividad (downtime) debido a reinicios o cambios en la configuración. El escalamiento horizontal implica agregar múltiples instancias y distribuir la carga mediante balanceadores, permitiendo mantener la alta disponibilidad. Este enfoque requiere arquitecturas stateless, donde las aplicaciones no dependen del estado local, facilitando la replicación. En arquitecturas modernas, el cómputo y el almacenamiento pueden escalar de forma independiente. Además, el proceso puede automatizarse mediante auto scaling, ajustando dinámicamente la capacidad según métricas de rendimiento. Sin embargo, escalar horizontalmente entre zonas o regiones puede introducir costos adicionales de transferencia de datos y latencia, y en entornos de nube pública el rendimiento puede verse afectado por el fenómeno de multitenancy (ej. “vecino ruidoso”).
## 🔗 Connections
- [[Cloud Público]] , [[IaaS vs PaaS vs SaaS]] , [[Redundante en zona en el cloud]] . [[Redundante geo-redundante en el cloud]]
