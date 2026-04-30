---
Fecha de creación: 2026-02-26 15:25
Fecha de Modificación: 2026-02-26 15:25
tags: 
Tema:
---


## 📚 Idea/Concepto 

La redundancia local en el cloud es un mecanismo de tolerancia a fallos que replica datos dentro de una misma Zona de Disponibilidad (AZ) o clúster, distribuyéndolos en diferentes dominios de fallo (como racks o nodos) con infraestructura física independiente. Los sistemas fragmentan la información en bloques (chunks) que se almacenan en múltiples máquinas, permitiendo recuperación rápida ante fallos de hardware individuales. Esta replicación suele ser sincrónica, lo que garantiza consistencia inmediata y baja latencia en comparación con replicaciones entre zonas o regiones. Además, la redundancia local no solo abarca datos, sino también la infraestructura de soporte, incluyendo sistemas de energía (UPS, generadores) y redes redundantes, para evitar puntos únicos de fallo. Sin embargo, su alcance es limitado: no protege contra fallos a nivel de centro de datos completo. Por ello, se considera el nivel mínimo de protección y debe complementarse con redundancia zonal o regional.
## 🔗 Connections
- [[Cloud Público]] , [[Redundante en zona en el cloud]] , [[IaaS vs PaaS vs SaaS]]

