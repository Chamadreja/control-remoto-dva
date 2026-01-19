# Control Remoto para Dispositivos DVA (Actualizado)

Este proyecto consiste en un sistema de control inalámbrico para dispositivos de búsqueda de víctimas de avalanchas (DVA), diseñado para optimizar las prácticas de rescate en nieve.

## Evolución del Proyecto
Originalmente diseñado como un sistema híbrido, el proyecto ha evolucionado hacia una **solución centrada en software**, donde la gestión y el control se realizan íntegramente a través de una aplicación desarrollada en **Qt/C++**.

## Funcionalidades Actuales (Interfaz Qt)
La nueva versión de la aplicación incluye:
- **Gestión Centralizada:** Control total de los nodos enterrados desde una única interfaz de usuario.
- **Nuevas Funcionalidades:** Mapa para fijar los DVA antes de enterrarlos, Guardado de Sesiones, Estrategias de envio del Mensaje LoRa (intentos/rafaga y cantidad), nueva forma de Encendido de los DVA, mediante una alarma dada por una fecha o por duración (cuanto tiempo estara el microcontrolador "dormido"), Monitor de Eventos.
- **Visualización:** Interfaz optimizada para el uso en terreno.

## Hardware y Comunicación
- **Protocolo:** Comunicación LoRa P2P para asegurar alcance en entornos de montaña.
- **Hardware:** PCBs doble faz fabricados mediante CNC, integrando módulos de comunicación de largo alcance.

## Documentación de Referencia
Se incluye el informe inicial de **Arquitectura de Software** como base histórica del diseño, aunque el sistema actual cuenta con las mejoras y funcionalidades mencionadas anteriormente.

> Actualmente no se tiene un Informe Final
