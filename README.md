//Control servo with an ESP32
#include <Arduino.h>
#include <ESP32Servo.h>

#define PIN_SERVO 13
Servo myServo;

void setup() {
    myServo.attach(PIN_SERVO);
}

void loop() {
  for(int pos = 0; pos < 180; pos += 20);
  myservo.write (pos);
delay(500);
}

myServo.write(0);
delay(1000);
}

