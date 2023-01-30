# Instalar_Platformio
Instrucciones para empezar con Arduino en VSCode
## Paso 1: Instalar el driver ch340 para poder manejar los arduinos con ese chip.
Hay algunas placas Arduino que utilizan el diseño original de los fabricantes para controlar el puerto USB de la placa. Con esas no hay que hacer nada.

Hay otras placas que usan el chip ch340 para conectarse por USB al ordenador. Según el sistema operativo, puede ser necesario instalar el controlador de este chip en el ordenador. Es necesario para usar el programa IDE de Arduino.

Se usarán las instrucciones de esta página web o de cualquier otra que busquéis en Internet:
[instalar driver ch340](https://programmerclick.com/article/87861702877/)

Después de esto podríamos descargar y probar el funcionamiento del IDE de Arduino, pero vamos a ir a otra opción a continuación.

## Paso 2: Buscar Platformio en las extensiones de VSCode.
Abrimos el programa y vamos a la pestaña de extensiones:
![Extensiones](imagenes/extensiones.png)

Allí buscaremos la extensión y la instalamos:
![Extensiones](imagenes/instalar.png)

## Paso 3: panel *home*.
Platformio nos instala una nueva pestaña de herramientas, con la imagen de una hormiga:
![Extensiones](imagenes/icono.png)