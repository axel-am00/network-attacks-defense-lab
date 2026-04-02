# Laboratorio de Ataques y Defensa en Redes (Capa 2 y MITM)

## Descripción

Este proyecto presenta un laboratorio avanzado de ciberseguridad enfocado en ataques de red de Capa 2, técnicas Man-in-the-Middle (MITM) y la implementación de infraestructuras de red empresariales seguras.

El laboratorio combina escenarios ofensivos y defensivos en entornos simulados que representan redes corporativas reales.

---

## Escenarios implementados

### Infraestructura de red empresarial

* Diseño de red de dos sedes (Principal y Sucursal)
* Segmentación mediante VLANs (10, 20, 30)
* Implementación de EtherChannel con LACP
* Enrutamiento dinámico con OSPF (área única)
* NAT/PAT para acceso a Internet
* Despliegue de servicios DHCP y DNS

---

## Ataques realizados

### Ataques de Capa 2

* DHCP Spoofing
* DHCP Starvation
* Ataque STP (Root Bridge)
* CDP Flooding (Denegación de Servicio)

### Ataques Man-in-the-Middle (MITM)

* ARP Spoofing
* Servidor DHCP Rogue

### Ataques a servicios de red

* DNS Spoofing
* DNS Poisoning

### Técnicas avanzadas de explotación

* VLAN Hopping (ataque mediante DTP)
* Ataques VTP (modificación no autorizada de VLANs)

---

## Herramientas y tecnologías

* Kali Linux
* Wireshark
* GNS3
* PnetLab (laboratorio virtual de redes)

---

## Objetivos

* Identificar vulnerabilidades en redes conmutadas
* Ejecutar ataques reales en entornos controlados
* Analizar el impacto de ataques MITM
* Evaluar debilidades en protocolos y configuraciones de red

---

## Medidas de mitigación

* DHCP Snooping
* Dynamic ARP Inspection (DAI)
* Port Security
* Deshabilitar Dynamic Trunking Protocol (DTP)
* Configuración segura de Spanning Tree Protocol (STP)
* Implementación de prácticas seguras de DNS

---

## Demostración y análisis

Este laboratorio está documentado mediante demostraciones prácticas en video, donde se muestra:

* Ejecución de los ataques en entornos simulados
* Análisis del comportamiento de la red durante el ataque
* Aplicación de medidas de mitigación (hardening)
* Verificación de la efectividad de las soluciones implementadas

Los videos sirven como evidencia práctica del funcionamiento de cada técnica.

---

## Videos demostrativos

A continuación se presentan demostraciones prácticas de los ataques realizados, junto con su análisis y las medidas de mitigación aplicadas:

### ARP Spoofing (MITM) y análisis del tráfico

Enlace: https://www.youtube.com/watch?v=BuANWy_9Wdg

### Ataque DHCP Rogue en red empresarial

Enlace: https://www.youtube.com/watch?v=DqDTrkv0V7o

### VLAN Hopping mediante DTP

Enlace: https://www.youtube.com/watch?v=rZSQLAGWwjk

### DNS Spoofing y redirección de tráfico

Enlace: https://www.youtube.com/watch?v=rZSQLAGWwjk

---

## Análisis de impacto

Los ataques realizados en este laboratorio evidencian riesgos críticos en entornos empresariales, tales como:

* Intercepción del tráfico de red
* Redirección de usuarios hacia sistemas maliciosos
* Interrupción de servicios de red

Estas vulnerabilidades pueden comprometer la confidencialidad, integridad y disponibilidad de la información si no se implementan controles de seguridad adecuados.

---

## Autor

Axel José Acosta Medina
