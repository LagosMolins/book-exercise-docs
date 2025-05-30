# Constrained Device Application (Connected Devices)

## Lab Module 10

Be sure to implement all the PIOT-CDA-* issues (requirements) listed.

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
Lo que hice fue configurar el broker Mosquitto y el cliente CDA para que usen TLS, con el objetivo de tener una comunicación segura y cifrada usando MQTT, también configuré cómo el CDA procesa comandos de actuadores y datos de sensores, tanto con MQTT como con CoAP.

How does your implementation work?
Para la parte de TLS, generé y configuré certificados con OpenSSL y ajusté la configuración del broker y los clientes para usar cifrado cuando hace falta. Finalmente, para procesar comandos y datos, 
actualicé las clases para que escuchen los mensajes entrantes, los decodifiquen, y tomen acciones según corresponda, como activar un actuador si los sensores detectan algo relevante.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/LagosMolins/python-components/tree/labmodule10


### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- 
- 
- 

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- MqttClientPerformanceTest
- 
- 

EOF.
