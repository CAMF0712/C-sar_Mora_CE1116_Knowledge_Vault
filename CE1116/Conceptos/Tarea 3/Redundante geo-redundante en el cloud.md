---
Fecha de creación: 2026-02-26 15:25
Fecha de Modificación: 2026-02-26 15:25
tags: 
Tema:
---


## 📚 Idea/Concepto 

La redundancia geo-redundante en el cloud es una estrategia de Disaster Recovery (DR) que replica datos y servicios entre múltiples regiones geográficas completamente aisladas, cada una con infraestructura independiente de red, energía y control. Está diseñada para proteger contra fallos catastróficos a nivel regional, proporcionando el máximo nivel de resiliencia. La replicación entre regiones suele ser asíncrona, debido a las limitaciones físicas de latencia en la transmisión de datos a larga distancia, lo que introduce un compromiso entre consistencia y disponibilidad. Para gestionar el failover entre regiones, se utilizan Global Load Balancers junto con patrones arquitectónicos como Active-Active (múltiples regiones activas simultáneamente) o Active-Passive (una región primaria y otra de respaldo), permitiendo redirigir el tráfico automáticamente ante fallos. Este modelo implica desafíos como alta latencia, costos de transferencia de datos entre regiones, y dependencia de infraestructura física subyacente (como cables de fibra óptica intercontinentales). Además, los puntos de presencia (PoP) permiten acercar el acceso a los usuarios finales, reduciendo la latencia percibida.

## 🔗 Connections
- [[Cloud Público]] , [[Cloud Híbrido (Hybrid cloud)]] , [[Redundante en zona en el cloud]] , [[Escalamiento horizontal y vertical en el cloud]] , [[IaaS vs PaaS vs SaaS]]
