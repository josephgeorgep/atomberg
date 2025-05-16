# Atomberg Fan ESPHome Integration (TYWE1S Module)



This ESPHome configuration provides local control for Atomberg fans with Tuya-based WiFi modules (TYWE1S), enabling integration with Home Assistant while maintaining all original remote functionality.

## Features

- 🌀 **Full fan control** (on/off, speed 1-6 including boost)
- 💡 **LED control** (on/off)
- 📶 **WiFi signal monitoring**
- 🔄 **Automatic ON** after power cycle helps mimmics a regular fan


## Soldering Insights

Only ground can be soldered in the given pads (marked in red). None of the other pads here works!

![image alt](https://github.com/josephgeorgep/atomberg/blob/d3205859a1c2604d09c4c08dceb7bda9cfacec2c/assets/board.png)


![image alt](https://github.com/josephgeorgep/atomberg/blob/d3205859a1c2604d09c4c08dceb7bda9cfacec2c/assets/TYWE1S.png)

The pins **IO0**, **3.3V**, **TX**, **RX** should be soldered directly to the MCU as shown in the pinout.
Don't forget to gnd GPIO0 (IO0) for taking the MCU into flashing mode :) 

Happy flashinggggg ;)
