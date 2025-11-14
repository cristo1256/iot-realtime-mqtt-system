# iot-realtime-mqtt-system

# IoT Real-Time System with MQTT, Flask & SQLite

Este proyecto implementa un sistema IoT distribuido que utiliza **MQTT** como middleware de comunicación, **Flask** como servidor central y **SQLite** como base de datos para almacenar métricas de sensores simulados.

Los sensores publican datos de temperatura y humedad en un broker MQTT (Mosquitto). Un subscriber escucha los mensajes y los reenvía al servidor Flask, que los almacena en SQLite y expone una API REST para consultas.

## Características principales
- Publicación periódica de métricas IoT con **paho-mqtt**
- Middleware de comunicación con **Mosquitto**
- Servidor central con **Flask** y almacenamiento en **SQLite**
- API REST para consultar datos históricos
- Arquitectura extensible para más sensores y métricas

## Tecnologías utilizadas
- Python (paho-mqtt, Flask, sqlite-utils)
- Mosquitto (Broker MQTT)
- SQLite (base de datos ligera)
