---
Fecha de creación: 2026-02-26 15:25
Fecha de Modificación: 2026-02-26 15:25
tags: 
Tema:
---


## 📚 Idea/Concepto 

La redundancia en zona en el cloud es un mecanismo de alta disponibilidad que distribuye cargas de trabajo y datos en múltiples Zonas de Disponibilidad (AZ) dentro de una misma región, donde cada zona opera sobre infraestructura física independiente (energía, red y refrigeración). Las aplicaciones se despliegan en clústeres separados por zona y los datos se replican entre ellas, típicamente de forma sincrónica, para garantizar consistencia y evitar pérdida de información durante un failover. Ante la caída de una zona completa, una capa de orquestación —como balanceadores de carga o planos de control— detecta el fallo y redirige automáticamente el tráfico hacia zonas disponibles, manteniendo la continuidad del servicio. Este modelo mejora la resiliencia frente a fallos de centros de datos completos, aunque introduce compromisos como mayor latencia y costos adicionales por transferencia de datos entre zonas.

## 🔗 Connections
- [[Cloud Público]] , [[Redundante localmente en el cloud]] , [[Redundante geo-redundante en el cloud]] , [[Escalamiento horizontal y vertical en el cloud]] , [[Virtual Private Cloud (VPC)]]
