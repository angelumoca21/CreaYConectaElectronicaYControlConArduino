# Introducción a Arduino: placa, entradas y salidas.

## 1.¿Qué es Arduino?

Imagina que Arduino es un pequeño computador, pero a diferencia de una laptop, no tiene pantalla ni teclado. Su trabajo es leer lo que pasa afuera (con sensores) y decidir qué hacer (encender luces o mover motores).

## 2.Anatomía de la Placa (Las partes del cuerpo)

El Microcontrolador (El Cerebro): Es el chip negro rectangular. Ahí es donde guardamos las instrucciones que escribimos.

El Puerto USB (La Boca): Por aquí "alimentamos" a Arduino con el código que hacemos en la computadora. También le da energía.

Jack de Alimentación (El Estómago): Sirve para conectar una batería si queremos que nuestro proyecto funcione sin estar pegado a la computadora.

Los Pines (Los Dedos): Son los hoyitos con números. Sirven para conectarse con otros componentes.

![Arduino](./images/arduino.png)

![Arduino2](https://3dpellet.com/img/tutoriales/arduino/primeros-pasos/introduccion/arduino-partes.webp)

## 3.Entradas y Salidas: ¿Cómo se comunica?

Arduino tiene dos formas de interactuar:
- **A. Salidas (Output) - "Arduino Actúa" 📢**
Es cuando el cerebro envía electricidad hacia afuera para que algo suceda.
Ejemplos: Encender un LED, hacer sonar una bocina (piezo), girar un motor.
Analogía: Es como cuando tu cerebro le dice a tu mano: "¡Saluda!".

- **B. Entradas (Input) - "Arduino Siente" 👀**
Es cuando el cerebro recibe información del mundo exterior.
Ejemplos: Un botón presionado, un sensor que detecta luz, un sensor que mide la distancia.
Analogía: Es como cuando tus ojos ven que el semáforo está en rojo y le envían esa información a tu cerebro.

![EntradasSalidasArduino](https://iaciduino.enp.unam.mx/wp-content/uploads/2023/04/sistema-electronico-768x432.png)

## 4.Señales Digitales vs. Analógicas: ¿Cómo habla el mundo? 🚥

Arduino puede entender dos tipos de "idiomas" o señales. Imagina que son formas distintas de recibir información:
- **1. Señales Digitales⚪⚫**
Es la señal más simple. Solo tiene dos estados posibles: ENCENDIDO o APAGADO (en programación usamos 1 y 0). No hay puntos medios.
Ejemplo de la vida real: Un interruptor de luz. La luz está prendida o está apagada.
En Arduino: Un botón (pulsado o no pulsado) o un LED (encendido o apagado).
Cómo se ve: Como una escalera cuadrada. Sube de golpe y baja de golpe.

![SeñalDigital](https://codiziapp.com/storage/subtopics/3_3.jpg)

- **2. Señales Analógicas (La Perilla) 🌀**
Estas señales son más detalladas. Pueden tener muchos valores intermedios. No es solo "sí o no", es "¿qué tanto?".
Ejemplo de la vida real: El control de volumen de un radio o una perilla para atenuar la luz (dimmer). Puedes tener un poquito de volumen, la mitad, o todo.
En Arduino: Un sensor de luz (LDR) que detecta si está "un poco oscuro" o "muy brillante", o un potenciómetro.
Cómo se ve: Como una montaña rusa o una ola del mar. Sube y baja suavemente.

![SeñalDigital](https://i0.wp.com/fidiasrodriguez.com/wp-content/uploads/2019/06/3-bit_resolution_analog_comparison.png?w=724&ssl=1)

## 5.Parpadeo de LED

### Conexión física

![ConexionFisica](https://github.com/angelumoca21/TallerArduinoPILARES/blob/main/1.Blink/imagenes/conexionFisica.png)

### Diagrama
![Diagrama](https://github.com/angelumoca21/TallerArduinoPILARES/blob/main/1.Blink/imagenes/diagrama.png)

### Reto: Semáforo (verde 5s, amarillo 1.5s y rojo 3s)

## 6.Botón

### Conexión física 2 terminales

![ConexiónFisica2Terminales](https://github.com/angelumoca21/TallerArduinoPILARES/blob/main/2.Push_Button/imagenes/conexionFisica2.png)

### Conexión física 4 terminales

![ConexiónFisica4Terminales](https://github.com/angelumoca21/TallerArduinoPILARES/blob/main/2.Push_Button/imagenes/conexionFisica4.png)

### Diagrama

![Diagrama](https://github.com/angelumoca21/TallerArduinoPILARES/blob/main/2.Push_Button/imagenes/diagrama.png)

## 7.LED RGB

### Conexión física

![ConexionFisica](https://github.com/angelumoca21/TallerArduinoPILARES/blob/main/LED_RGB/imagenes/rgb.png)

![Bloques de programación](https://github.com/angelumoca21/TallerArduinoPILARES/blob/main/LED_RGB/imagenes/rgbBloques.png)

## 8.Potenciometro

### Conexión física

![ConexionFisica](https://github.com/angelumoca21/TallerArduinoPILARES/blob/main/Potenciometro/imagenes/potenciometro.png)

![Bloque de código](https://github.com/angelumoca21/TallerArduinoPILARES/blob/main/Potenciometro/imagenes/potBloques.png)