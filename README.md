# Finnish School – mBot2 Programming Projects

## Introduction

In our ICT lessons, we use **mBot2** to learn Python programming and practise different coding activities.

We use the CyberPi screen and RGB LEDs to display information and control different colours.

## Activity 1 – Display Your Name

In this activity, we display our first name on the CyberPi screen.

Python code:

```python
import cyberpi

cyberpi.display.show_label("Your Name", 24, 0, 0, 1)
```

**Explanation:** The program displays our first name on the robot's screen.

## Activity 2 – Display Your Surname and Grade

In this activity, we display our surname and grade on separate lines.

Python code:

```python
import cyberpi

cyberpi.display.show_label("Your Surname", 24, 0, 0, 1)
cyberpi.display.show_label("Grade 10", 24, 0, 30, 2)
```

**Explanation:** The program displays our surname and grade separately on the CyberPi screen.

## Activity 3 – Clear the Screen

In this activity, we remove all the displayed text from the screen.

Python code:

```python
import cyberpi

cyberpi.display.clear()
```

**Explanation:** The `clear()` command removes the information displayed on the screen.

## Activity 4 – Change the Font Size

In this activity, we change the size of the displayed text.

Python code:

```python
import cyberpi

cyberpi.display.show_label("Hello!", 16, 0, 0, 1)
cyberpi.display.show_label("Hello!", 24, 0, 30, 2)
cyberpi.display.show_label("Hello!", 32, 0, 60, 3)
```

**Explanation:** We use different font-size values to display text in different sizes.

- 16 – Small
- 24 – Medium
- 32 – Large

## Activity 5 – Control the RGB LEDs

In this activity, we change the RGB LED colours to red, green, and blue.

Python code:

```python
import cyberpi
from time import sleep

cyberpi.led.on("red")
sleep(1)

cyberpi.led.on("green")
sleep(1)

cyberpi.led.on("blue")
sleep(1)

cyberpi.led.off("all")
```

**Explanation:** The program changes the RGB LED colour every second. At the end, all LEDs are turned off.

## What I Have Learned

Through these five activities, I have learned how to:

1. Display text on the CyberPi screen.
2. Display different lines of information.
3. Clear the screen.
4. Change the font size.
5. Control RGB LED colours using Python.

These activities help me develop my *programming and problem-solving skills*.

## Useful Website

[mBlock Official Website](https://mblock.cc/)
