# Arduino LED Simulation

A beginner-friendly Arduino project that demonstrates how to control an LED using an Arduino Uno.
The project is simulated using the **Wokwi Arduino Simulator**, making it possible to test and run the circuit without physical hardware.

---

## Project Overview

This project introduces the fundamentals of Arduino programming and electronics by controlling an LED connected to an Arduino board.

It helps beginners understand:

* Digital output pins
* Basic Arduino code structure
* Controlling hardware using software
* Circuit simulation using Wokwi

---

## Components Used

* Arduino Uno
* LED
* Resistor
* Breadboard (virtual in simulation)
* Jumper wires

---

## Circuit Diagram

The LED is connected to one of the Arduino digital pins through a resistor.
The Arduino program sends HIGH and LOW signals to control the LED.

Basic connection:

Arduino Digital Pin → Resistor → LED → Ground

---

## Arduino Code

```cpp
void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(1000);

  digitalWrite(13, LOW);
  delay(1000);
}
```

This program makes the LED blink every second.

---

## Files in This Project

```
sketch.ino      → Arduino program
diagram.json    → Wokwi circuit configuration
wokwi.toml      → Wokwi project settings
```

---

## How to Run the Simulation

1. Open the project in the Wokwi simulator.
2. Start the simulation.
3. The LED will blink continuously every second.

You can also modify the delay values to change the blinking speed.

---

## Learning Outcomes

After completing this project you should understand:

* The structure of an Arduino program
* How to configure pins using `pinMode`
* How to control components using `digitalWrite`
* How to simulate circuits using Wokwi

---

## Author

**Flevian Ochoka Ahithopel**
Software Developer | IT Trainer | Tech Enthusiast

---

## License

This project is open source and available for educational use.
