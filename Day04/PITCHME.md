---
# Robotics

#### Day 4 - More Programming
---
## Do Now

See if you can add something else to your circuit
---
## Core Concepts

* Wiring up electronics
* How Arduino code functions
* Simple Arduino built-in functions
* PWM
---
## Review

* Arduino language is based on C++
* `void setup(){}` runs once
* `void loop(){}` runs forever
---
## Last class

```
void setup(){
    pinMode(13, OUTPUT);
}

void loop(){
    digitalWrite(13, HIGH);
    delay(1000);
    digitalWrite(13, LOW);
    delay(1000);
}
```
---
# PWM
---
## PWM

* Pulse width modulation
* Simulates analog outputs
* Pulses digital signals very quickly
---
## New Function

* `analogWrite(pin, level);`
* `analogWrite(9, 128);`
* Values are 0-255
---
## Try it together

* Hook an LED up to pin 9
* Make the LED fade in and out
---
## Independent Practice

* Wire up an RGB LED
* Light up the LED in a repeating pattern of colors
* Submit a link in Classroom to the  "Day 4 - PWM" assignment