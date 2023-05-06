# Semaforo para invidentes
![Tinkercad](./img/ArduinoTinkercad.jpg)


## Integrantes 
- Belen Soria
- Thiago Rodríguez
- Ivan Sacks
- Melina Silva
- Franco Sofia


## Proyecto: Dojo, Semaforo para invidentes.
![Tinkercad](./img/SemaforoBuzzer.png)


## Descripción
El semaforo cumple la funcion de, si bien ser un semaforo usual, también es un semaforo para invidentes, ya que cuenta con un pienzo. Este al hacer sonido durante la luz roja, le indica al usuario cuando no pasar.

## Función principal
Esta funcion se encarga de encender los leds y buzzer, y apagarlos.

LED_VERDE_A, LED_VERDE_B, TIEMPO_VERDE, LED_AMARILLO_A, LED_AMARILLO_B, TIEMPO_AMARILLO,
LED_ROJO_A, LED_ROJO_B, BUZZER son #define que utilizamos para agregar los leds, y el buzzer asociandolo a pines de la placa arduino.

En la funcion loop, llama las funciones PrenderApagarLeds, enviando los parametros, y PrenderApagardLedRojoBuzzer la cual cuando enciende, también suena el buzzer.
 
~~~ C (lenguaje en el que esta escrito)
void loop()
{
  PrenderApagarLeds(LED_VERDE_A,LED_VERDE_B, TIEMPO_VERDE);
  PrenderApagarLeds(LED_AMARILLO_A, LED_AMARILLO_B, TIEMPO_AMARILLO);
  PrenderApagardLedRojoBuzzer(LED_ROJO_A,LED_ROJO_B, BUZZER);
  PrenderApagarLeds(LED_AMARILLO_A, LED_AMARILLO_B, TIEMPO_AMARILLO);
}
~~~

## :frog: Link al proyecto
- [proyecto](https://www.tinkercad.com/things/i5YadsTv6GA-1d-dojo-d-soria/editel?sharecode=NJgFzQIbBMTWZXhFoCaBf0GYQ75TVjQc9fx_lACDTSc)

---
### Fuentes
- [Consejos para documentar](https://www.sohamkamani.com/how-to-write-good-documentation/#architecture-documentation).

- [Lenguaje Markdown](https://markdown.es/sintaxis-markdown/#linkauto).

- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

- [Tutorial](https://www.youtube.com/watch?v=oxaH9CFpeEE).

- [Emojis](https://gist.github.com/rxaviers/7360908).

---




