# Monitoring-Grafana-Azure-On-premises

Este proyecto consiste en dos partes principales:

1.  **Monitorización de una VM en Azure con Azure Managed Grafana y Azure Monitor.**
    
2.  **Monitorización de una VM en On-Premises con Grafana, Prometheus y Node Exporter.**

   #
 ![image](https://github.com/user-attachments/assets/37f5d06f-7c69-4c30-8ea6-4bea66c6781e)   

## Descripción

En este proyecto, implementamos soluciones de monitorización para dos entornos distintos: uno en la nube (Azure) y otro en un entorno local (On-Premises). La monitorización está orientada a medir el rendimiento y estado de las máquinas virtuales (VMs) en ambos entornos, enviando alertas cuando se detectan ciertos umbrales.

### Parte 1: Monitorización de VM en Azure

En esta sección, utilizamos **Azure Managed Grafana** para visualizar métricas y configuramos **Azure Monitor** para generar alertas basadas en umbrales definidos (como uso de CPU). Esta parte de la solución ayuda a monitorear el rendimiento de las máquinas virtuales en la nube de Azure.

### Parte 2: Monitorización de VM On-Premises

En esta sección, utilizamos **Grafana**, **Prometheus**, y **Node Exporter** para obtener métricas del sistema de una máquina virtual que se ejecuta en un entorno local (On-Premises). **Prometheus** recopila las métricas y **Grafana** las visualiza. Usamos **Node Exporter** para exponer las métricas del sistema, como la utilización de CPU..


## ¿Qué es Grafana?   

**Grafana** es una plataforma de código abierto para la visualización de métricas y logs, que permite crear paneles interactivos para monitorear y analizar datos de diversas fuentes. Es ampliamente utilizada para la monitorización de infraestructuras y aplicaciones. En este proyecto, Grafana se utiliza para crear visualizaciones de las métricas recolectadas de las máquinas virtuales, ya sea en Azure o en un entorno On-Premises.

Grafana se conecta a diversas fuentes de datos, como Prometheus, Azure Monitor, entre otras, para ofrecer un panorama claro del rendimiento y estado de los sistemas monitoreados.


#
Este proyecto fue desarrollado por **Ángel Barahona García**. Puedes conectar conmigo a través de [www.linkedin.com/in/angelbarahonagarcía](http://www.linkedin.com/in/angelbarahonagarc%C3%ADa)
