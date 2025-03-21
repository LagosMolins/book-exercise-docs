# Constrained Device Application (Connected Devices)

## Lab Module 03

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
Esta implementación agrega la capacidad de simulación de datos a la CDA, incorporando sensores virtuales para medir temperatura, humedad y presión. Utilizando un generador de datos, se simulan estos valores y se configuran umbrales, que en caso de ser superados se inica un actuador.

How does your implementation work?
Los sensores simulados generan datos que son empaquetados en objetos de telemetría, que contienen información adicional sobre el dispositivo. Cuando los valores de los sensores exceden los umbrales establecidos, se activa un actuador. Esto permite probar y validar la interacción entre los sensores y actuadores sin hardware físico.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/LagosMolins/python-components/tree/labmodule03

### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- ActuatorDataTest
- SensorDataTest
- SystemPerformanceDataTest
-  HumiditySensorSimTaskTest
-  PressureSensorSimTaskTest
-  TemperatureSensorSimTaskTest
-  HumidifierActuatorSimTaskTest
-  HvacActuatorSimTaskTest

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- SensorAdapterManagerTest
- ActuatorAdapterManagerTest
- DeviceDataManagerNoCommsTest
- ConstrainedDeviceAppTest

EOF.
