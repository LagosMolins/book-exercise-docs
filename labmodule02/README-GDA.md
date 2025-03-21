# Gateway Device Application (Connected Devices)

## Lab Module 02

Be sure to implement all the PIOT-GDA-* issues.

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
La implementación en GDA tiene como objetivo agregar características de monitoreo de rendimiento del sistema, como la recopilación de métricas de uso de CPU y memoria. Estas métricas proporcionan datos básicos sobre el rendimiento del sistema.

How does your implementation work?
La implementación sigue la estructura del GDA en Java y agrega la funcionalidad de recolección de datos de rendimiento del sistema. El código se encarga de la recolección de datos de uso de CPU y memoria en intervalos definidos, registrándolos para análisis posterior.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/LagosMolins/java-components/tree/labmodule02


### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- ConfigUtilTest
- SystemCpuUtilTest
- SystemMemUtilTaskTest

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- GatewayDeviceAppTest
- SystemPerformanceManagerTest
- 

EOF.
