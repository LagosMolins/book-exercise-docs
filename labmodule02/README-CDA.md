# Constrained Device Application (Connected Devices)

## Lab Module 02

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
Esta implementación añade funcionalidades de monitoreo del rendimiento del sistema a las aplicaciones CDA. Recoge métricas básicas como la utilización de CPU y memoria.

How does your implementation work?
La implementación crea el módulo SystemPerformanceManager para gestionar la recolección de datos de rendimiento. Este módulo se conecta a la aplicación principal del CDA y coordina las tareas, como SystemCpuUtilTask y SystemMemUtilTask, que recogen los datos de la CPU y memoria.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/LagosMolins/python-components/tree/labmodule02

### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- ConfigUtilTest
- SystemCpuUtilTest
- SystemMemUtilTest

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- SystemPerformanceManagerTest
- ConstrainedDeviceAppTest
- 

EOF.
