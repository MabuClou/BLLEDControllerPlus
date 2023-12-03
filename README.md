## This is a fork of BL Led Controller, originally created by [DutchDeveloper] ( [https://dutchdevelop.com/](https://dutchdevelop.com/what-is-a-blledcontroller/) )
I am going to make use of the additional PINs provided on the board.

I am going to connect
* a switch to turn on white light
* a button to cycle through all colors

Let's see how this works.

## Additional PINs
<img src="pin labeling on backside.jpg" height="300">
The labeling of these PINs is off. Here is the correct usage:

| | | |
| - | - | - |
| GND | GPIO 17 | GPIO 16 |
| 5V | GPIO 4 | GPIO 2 |

Be careful: the ESP32 runs with 3.3V! If you feed 5V to the IO PINs it will get damaged.
