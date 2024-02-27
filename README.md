# Archivos de Pruebas de Comunicación Serial Bidireccional entre dos Arduinos (No Interrupciones) 🔄🤖

Este proyecto proporciona archivos de pruebas para establecer una comunicación serial bidireccional entre dos placas Arduino utilizando el puerto serial UART. El objetivo es demostrar la comunicación entre dos dispositivos Arduino sin usar interrupciones, lo que puede ser útil en casos donde las interrupciones no son factibles o deseables.

## Descripción 🛠️

El proyecto incluye dos partes principales:

- **Código para Arduino A:** En la carpeta `Arduino_A` encontrarás el código para cargar en la primera placa Arduino (Arduino A). Este código configura el Arduino para enviar datos a través del puerto serial UART.

- **Código para Arduino B:** En la carpeta `Arduino_B` encontrarás el código para cargar en la segunda placa Arduino (Arduino B). Este código configura el Arduino para recibir los datos enviados por el Arduino A a través del puerto serial UART y responder con una confirmación.

## Requisitos 📦

- Dos placas Arduino (p. ej., Arduino Uno o Arduino Nano)
- Cable USB para la conexión de Arduino al ordenador
- Entorno de desarrollo Arduino instalado en tu sistema

## Uso 📝

1. **Clonar el Repositorio:** Clona este repositorio en tu sistema local utilizando Git.

2. **Cargar Código en los Arduinos:** Carga el código proporcionado en las respectivas placas Arduino utilizando el IDE de Arduino o tu entorno de desarrollo preferido.

3. **Conexión de los Arduinos:** Conecta los Arduinos entre sí en Rx y Tx para establecer una comunicación serial entre ellos.

4. **Monitor Serial:** Abre el monitor serial en el IDE de Arduino o en un terminal serie en tu ordenador para observar la comunicación entre los Arduinos. Deberías ver mensajes de confirmación de ambas placas Arduino.

## Contribuciones 🚀

¡Contribuciones son bienvenidas! Si tienes ideas para mejorar los archivos de pruebas, corregir errores o agregar nuevas características, no dudes en abrir un "issue" o enviar un "pull request".

## Créditos 🙌

Este proyecto fue creado por PICAIO SAS y está inspirado en proyectos similares de la comunidad de Arduino.

## Licencia 📝

Este proyecto está bajo la licencia [MIT](LICENSE).
