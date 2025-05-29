# Gateway Device Application (Connected Devices)

## Lab Module 08

Be sure to implement all the PIOT-GDA-* issues (requirements) listed.

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
Establece un servidor CoAP en el Gateway Device usando la biblioteca Californium, permitiendo la comunicación con el CDA mediante recursos personalizados para enviar y recibir datos IoT.

How does your implementation work?
Crea e integra recursos CoAP en CoapServerGateway, los vincula al DeviceDataManager, y gestiona solicitudes como GET y PUT, incluyendo soporte para OBSERVE y actualización de datos en tiempo real.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/LagosMolins/java-components/tree/labmodule08


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

- CoapClientToServerConnectorTest 
- 
- 

EOF.
