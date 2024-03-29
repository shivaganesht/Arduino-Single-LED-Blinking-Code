# Arduino Single LED Blinking

This Arduino project demonstrates the basic functionality of blinking a single LED using the Arduino IDE. The LED blinks on and off in intervals of three seconds.

## Installation

1. Clone this repository to your local machine using `https://github.com/shivaganesht/Arduino-Single-LED-Blinking-Code.git`
2. Open the LEDBLINK.ino file in the Arduino IDE.

## Circuit Connections and Reference Diagram

![Single LED Light Blinking Diagram](https://github.com/shivaganesht/Arduino-Single-LED-Blinking-Code/assets/69391183/5878c572-b53d-4854-beae-c8eeec182b1c)


## Usage

1. Connect your Arduino board to your computer.
2. Select the correct connected Arduino port.
3. Upload the code to your Arduino board. If you're unsure how to upload code to your Arduino board, please take a look at the [Arduino documentation](https://www.arduino.cc/en/Guide/HomePage)
4. The LED connected to the built-in pin on the Arduino board will start blinking at intervals of three seconds.

## Code Overview

```cpp
void setup()
{
    pinMode(LED_BUILTIN, OUTPUT); // Set the built-in LED pin as an output
}

void loop()
{
    digitalWrite(LED_BUILTIN, HIGH); // Turn the LED on
    delay(3000); // Wait for three seconds
    digitalWrite(LED_BUILTIN, LOW); // Turn the LED off
    delay(3000); // Wait for three seconds
}
```

If you want to change the duration of the light blinking, you can change the delay time in the code. The timing in the delay is in the format milliseconds (i.e., 1 second = 1000 milliseconds).

## Conclusion

This project provides a simple example of blinking an LED with Arduino. Feel free to modify the code to suit your requirements!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
