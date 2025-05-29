# Constrained Device Application (Connected Devices)

## Lab Module 09

Be sure to implement all the PIOT-CDA-* issues (requirements) listed.

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
Implementa un cliente CoAP en Python usando aiocoap, permitiendo al CDA comunicarse con el GDA mediante operaciones GET, PUT, POST y DELETE.

How does your implementation work?
Define una clase CoapClientConnector que utiliza métodos asíncronos para enviar solicitudes CoAP al servidor configurado. Cada operación maneja su respuesta y se integra con DeviceDataManager si está habilitado.

-A mayores ejecuté ConstrainedDeviceApp.py para probarlo junto con la ejecución del .jar de lab08 gda

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/LagosMolins/python-components/tree/labmodule09




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

- CoapClientConnectorTest
- 
- 

EOF.
