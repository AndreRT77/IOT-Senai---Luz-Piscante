# IOT-Senai - Luz-Piscante

# Luz Piscante
![giphy](https://github.com/user-attachments/assets/dd0a4663-ed76-47de-b71b-ed8573b56744)

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
