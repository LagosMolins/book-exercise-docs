# Gateway Device Application (Connected Devices)

## Lab Module 07

Be sure to implement all the PIOT-GDA-* issues (requirements) listed.

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
Permite que el Gateway Device se comunique con un broker MQTT mediante una clase MqttClientConnector que gestiona conexión, publicación y suscripción a temas.

How does your implementation work?
Inicializa y configura un cliente MQTT, define callbacks para eventos clave, y se integra en el DeviceDataManager para conectar, suscribirse o desconectarse según la configuración del sistema.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/LagosMolins/java-components/tree/labmodule07


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

- MqttClientConnectorTest
- MqttClientControlPacketTest
- 

EOF.
