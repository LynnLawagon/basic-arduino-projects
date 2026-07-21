# Basic Arduino Projects

## Traffic Light LED Sequence

This project contains a simple Arduino sketch that lights three LEDs in a sequence. It is intended as a beginner example for using digital output pins and timing with `delay()`.

### Files

- `traffic_light.ino` - Arduino sketch that turns three LEDs on and off in sequence.

### Wiring

Connect three LEDs to the Arduino as follows:
- LED1 -> digital pin 13
- LED2 -> digital pin 12
- LED3 -> digital pin 11
- Each LED should use a current-limiting resistor (220Ω to 330Ω) to ground.

### Behavior

The sketch does the following in a loop:
1. Turn on LED1, wait 200 ms
2. Turn on LED2, wait 200 ms
3. Turn on LED3, wait 200 ms
4. Turn off LED1, wait 300 ms
5. Turn off LED2, wait 300 ms
6. Turn off LED3, wait 300 ms

### Notes

- Make sure the Arduino is connected and the correct board/port are selected in the Arduino IDE.
- If you see compile errors, ensure the file is saved with the `.ino` extension and the pin numbers match your wiring.

