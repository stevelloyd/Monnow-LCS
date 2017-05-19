# Activity 1 (Act—light LEDs)

This activity is to show how you can:
-  create **actions**; flashing a string of LEDs which have been 'hacked' and attached to a Raspberry Pi
- sense people using a PIR (passive infrared) sensor—the same type that can be used for switching on outdoor lights

Find the Raspberry Pi with a string of lights attached. On the screen should be a Racket language display.

![](Activity%201.png)

You've already got some definitions provided. Make sure they're ready by pressing the *run* button. Now try them out. Type the function name into the *interactions* window and hit *enter* key. Something should happen!

## Actions

| function name   | what it does                 |
| --------------- | ---------------------------- |
| (flash-once)    | flash the leds once          |
| (flash-twice)   | flash the leds twice         |
| (flash-times n) | flash the leds several times |

## Sensing people

| function name   | what it does                                 |
| --------------- | -------------------------------------------- |
| (sense-person?) | check if the PIR sensor has detected someone |
| (alarm)         | a simple person alarm                        |

Try out (sense-person?) with the sensor covered by a sheet of paper. 
- What value does it return? 
- Now remove the sheet of paper and move around near the sensor. What happens now?

Try the (alarm) function. Explain what behaviour you see.




