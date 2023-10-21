# Arduino-Touch-Sensor-Esp32
 Touch Sensor e LED com um resistor aplicado para verificar 0 e 1. 

int LED_BUILTIN = 23;

void setup() {
   pinmode(LED_BUILTIN, OUTPUT);
 pinmode(TO, INPUT);
}

void loop() {
 if (TouchRead(TO) < 20) {
  digitalwrite(LED_BUILTIN, LOW);
 }
delay(100);
}

# up code placa > pressionar o botão “Io0” para que o código seja escrito na placa.
# conferir número do touch sensor correspondente a GPIO.
