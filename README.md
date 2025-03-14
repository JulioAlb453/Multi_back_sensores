# Proyecto API Publicadora IoT

Este proyecto utiliza **Go versión 1.23** y consta de una API publicadora con arquitectura hexagonal y enfoque **event-driven**. Está diseñado para manejar tópicos en **MQTT**, específicamente para proyectos IoT.

## Características
- **Arquitectura Hexagonal**: Facilita la mantenibilidad y escalabilidad del código.
- **Event-Driven**: Permite la gestión eficiente de eventos.
- **MQTT**: Manejo de tópicos para comunicación en proyectos IoT.
- **Eventos de Lectura de Sensores**: Implementación de eventos para capturar y procesar datos de sensores en tiempo real.

## Requisitos
- **Go 1.23**: Asegúrate de tener instalada la versión correcta de Go.

## Cómo Funciona
Para ejecutar el proyecto, utiliza el siguiente comando:

```sh
go run main.go