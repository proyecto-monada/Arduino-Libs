# Arduino-Libs
Librerias de Arduino necesarias para ejecutar el videojuego
Todas tienen que estar en la carpeta de librerías de Arduino allá donde la tengáis.

- Adafruit_BNO055
Necesaria para leer la IMU BNO055

- Adafruit_Sensor
Se usa junto con la anterior para leer la IMU

- ArduinoSerialCommand
Necesaria para establecer la comunicación serie con Unity. IMPORTANTE!! Cambiar en Unity>>Edit>>Project settings>>Player>>Configuration>>Api compatibility level al ".NET 2.0". Si no os sale esa opción pues cambiad al otro que tengáis hasta que compile.
