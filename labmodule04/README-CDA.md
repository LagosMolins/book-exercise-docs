# Constrained Device Application (Connected Devices)

## Lab Module 04

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
Se tuvierron que instalar multiples herraminetas (senseHat,pillow, pisense,...)
Esta implementación configura la integración de los sensores y actuadores en la CDA, utilizando el emulador Sense HAT, para controlar y visualizar. Se incorporan sensores para monitorear la humedad, temperatura y presión, y un actuador controla la pantalla LED para mostrar información o alertas específicas en función de los datos simulados.

How does your implementation work?
La CDA interactúa con el emulador Sense HAT para obtener datos de sensores y activar un actuador. Los datos de los sensores se procesan y el actuador controla la pantalla LED para mostrar información relevante, lo que permite simular un entorno. Al ejecutar los diferenrtes integration test se podian ver los diferentes valores por la pantalla LED.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/LagosMolins/python-components/tree/labmodule04


### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

-


### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- HumidityEmulatorTaskTest.py
- PressureEmulatorTaskTest.py
- TemperatureEmulatorTaskTest.py
- HumidifierEmulatorTaskTest.py
- HvacEmulatorTaskTest.py
- LedDisplayEmulatorTaskTest.py
- HumidifierActuatorSimTaskTest.py
- SenseHatEmulatorQuickTest.py
- SensorEmulatorManager.py
- ActuatorEmulatorManagerTest.py


EOF.
