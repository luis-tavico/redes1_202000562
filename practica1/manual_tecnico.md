# Manual Tecnico

## Introducción 📝

Este manual presenta los resultados obtenidos de la practica 1 del curso redes de computadoras 1, la cual se enfoca en la configuración de una red local empresarial de pequeña escala utilizando la plataforma Packet Tracer.

## Objetivo 📈

El objetivo principal de este manual es familiarizar a los usuarios con los conceptos básicos de diseño y configuración de redes locales empresariales a través de una práctica realizada en Packet Tracer. 

## Conocimientos Previo💡

Los conocimientos mínimos que deben tener las personas que operarán las páginas y deberán utilizar este manual son:

* Conocimientos respecto a los protocolos Ethernet, IP, ARP e ICMP.
* Conocimiento en configuración de máquinas virtuales VPC y switches de capa 2.
* Manejo en programa de simulacion de redes (Packet Tracer).


## Resultados ✅

A continuacion se mostraran capturas de pantallas de los resultados obtenidos al momento de ejecutar la simulacion de una red local pequeña en Packet Tracer.

### Topologia

![topologia](imagenes/topologia.png)

Topologia de la red.

### Configuracion de las VPC

![pc_admin](imagenes/pc_admin.png)

La imagen anterior representa la configuracion de la VPC perteneciente al nivel 1, area de administracion.

![pc_ger_sec](imagenes/pc_ger_sec.png)

La imagen anterior representa la configuracion de la VPC perteneciente al nivel 1, area de gerencia/secretaria.

![pc_aten_clien](imagenes/pc_aten_clien.png)

La imagen anterior representa la configuracion de la VPC perteneciente al nivel 1, area de antecion al cliente.

![pc_rh](imagenes/pc_rh.png)

La imagen anterior representa la configuracion de la VPC perteneciente al nivel 1, area de recursos humanos.

![pc_oficina_a](imagenes/pc_oficina_a.png)

La imagen anterior representa la configuracion de la VPC perteneciente al nivel 2, area de oficina A.

![pc_oficina_b](imagenes/pc_oficina_b.png)

La imagen anterior representa la configuracion de la VPC perteneciente al nivel 2, area de oficina B.

![pc_oficina_c](imagenes/pc_oficina_c.png)

La imagen anterior representa la configuracion de la VPC perteneciente al nivel 2, area de oficina C.

### Ping entre los Hosts

![ping1](imagenes/ping_192.168.62.10.png)

La imagen anterior representa el ping realizado de la VPC 192.168.62.10 (nivel 1, administracion) a la VPC 192.168.62.11 (nivel 1, gerencia/secretaria).

![ping1](imagenes/ping_192.168.62.14.png)

La imagen anterior representa el ping realizado de la VPC 192.168.62.13 (nivel 1, atencion al cliente) a la VPC 192.168.62.14 (nivel 1, recursos humanos).

![ping1](imagenes/ping_192.168.62.20.png)

La imagen anterior representa el ping realizado de la VPC 192.168.62.12 (nivel 1, atencion al cliente) a la VPC 192.168.62.20 (nivel 2, oficina A).

### Paquete ARP/ICMP

![arp](imagenes/arp.png)

La imagen anterior representa la captura de un paquete ARP.

## Construido con 🛠

Para la creacion de la practica se utilizaron los siguientes programas de simulacion de redes:

* [Packet Tracer](https://www.netacad.com/es/courses/packet-tracer) - Usado para la creacion total de la practica.

## Autor ✒

* [Pedro Luis Pu Tavico](https://github.com/luis-tavico)