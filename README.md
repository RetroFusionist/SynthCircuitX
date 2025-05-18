# SynthCircuitX
This project is a simple 8-key mini piano built using an Arduino Uno and simulated on the Wokwi platform. Each button is connected to a specific pin on the Arduino and is mapped to a musical note ranging from C4 to C5. When a button is pressed, the corresponding tone is played through a passive buzzer using the tone() function.

The code uses internal pull-up resistors with the INPUT_PULLUP mode, eliminating the need for external resistors. The note frequencies are defined in a separate pitches.h file, which allows for easy mapping and sound control.
