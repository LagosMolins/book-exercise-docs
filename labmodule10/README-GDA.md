# Gateway Device Application (Connected Devices)

## Lab Module 10

Be sure to implement all the PIOT-GDA-* issues (requirements) listed.

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
Me aseguré de que el cliente MQTT se suscriba a todos los temas que necesitamos una vez que la conexión esté lista. También mejoré cómo se procesan los datos de sensores y actuadores, por ejemplo, para activar el humidificador si hace falta.

How does your implementation work?
Configurar el cliente MQTT para que use archivos de certificados y credenciales si están disponibles, y me aseguro de que se conecte de forma segura. Una vez que está conectado, suscribo los temas que nos interesan de forma asíncrona para no bloquear nada. Después, el DeviceDataManager analiza los datos que llegan y decide qué hacer, como controlar el humidificador si detecta demasiada humedad. Las pruebas de rendimiento consisten en enviar muchísimos mensajes y medir cuánto tardan en ir y volver.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/LagosMolins/java-components/tree/labmodule10



### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- MqttConnectorTest
- 
- 

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- 
- 
- 

EOF.
