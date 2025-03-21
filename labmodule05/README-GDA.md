# Gateway Device Application (Connected Devices)

## Lab Module 05

Be sure to implement all the PIOT-GDA-* issues (requirements) listed.

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
Esta implementación habilita la serialización y deserialización de los datos en formato JSON en la GDA. Los datos de sensores y actuadores se convierten y almacenan de manera estandarizada.

How does your implementation work?
La GDA utiliza las clases DataUtil para convertir los datos de los sensores y actuadores en objetos JSON. Esta funcionalidad permite que los datos sean intercambiados y almacenados en formatos compatibles.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/LagosMolins/java-components/tree/labmodule05


### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- ActuatorDataTest 
- SensorDataTest 
- SystemPerformanceDataTest 
- SystemStateDataTest 
- DataUtilTest
- 
- 

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- DataIntegrationTest
- DeviceDataManagerNoCommsTest
- GatewayDeviceAppTest

EOF.
