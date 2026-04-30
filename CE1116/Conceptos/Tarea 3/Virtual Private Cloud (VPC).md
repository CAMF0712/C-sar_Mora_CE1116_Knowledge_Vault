---
Fecha de creación: 2026-02-26 15:25
Fecha de Modificación: 2026-02-26 15:25
tags: 
Tema:
---


## 📚 Idea/Concepto 

Una Virtual Private Cloud (VPC) es una red virtual aislada lógicamente dentro de una nube pública, implementada sobre infraestructura compartida mediante tecnologías de red definida por software (SDN). Permite definir un espacio de direcciones IP privadas utilizando notación CIDR, segmentado en subredes distribuidas a lo largo de múltiples zonas de disponibilidad dentro de una región. El flujo de tráfico se controla mediante tablas de enrutamiento, que determinan la comunicación interna entre subredes y la conectividad externa. La naturaleza pública o privada de una subred se define por su acceso a Internet Gateways o NAT Gateways, lo que permite gestionar salida y entrada de tráfico hacia internet. La seguridad se implementa en múltiples capas mediante Security Groups (a nivel de recurso) y Network ACLs (a nivel de subred). Además, la VPC puede extenderse hacia entornos externos u on-premises mediante conexiones seguras como VPN o enlaces dedicados, permitiendo arquitecturas híbridas.
## 🔗 Connections
- [[Cloud Público]] , [[Cloud Híbrido (Hybrid cloud)]] , [[IaaS vs PaaS vs SaaS]] , [[Redundante en zona en el cloud]]
