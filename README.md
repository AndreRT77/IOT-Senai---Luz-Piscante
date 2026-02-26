# IOT-Senai - Luz-Piscante

## TinkerCad
https://www.tinkercad.com/things/345Ky0E49jj-bodacious-bigery-juttuli?sharecode=T3R-FGQor44CcC69JvuMbQCMlEwHbhkhHenRVspM0ZY

## Simulação Wokwi
https://wokwi.com/projects/457024614553674753

## Código
#define LED_PIN 13 

void setup() {
  pinMode(LED_PIN, OUTPUT);
}

void loop() {
  digitalWrite(LED_PIN, HIGH);
  delay(200);
  digitalWrite(LED_PIN, LOW);
  delay(200);
}
