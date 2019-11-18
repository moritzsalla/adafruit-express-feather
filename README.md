# Adafruit Express Feather nRF52840

![Image](https://cdn-learn.adafruit.com/assets/assets/000/068/578/original/circuitpython_Screenshot_2019-01-02_at_12.04.27.png?1546446487)
 
- Bluetooth Low Energy and native USB support
- 'All-in-one' Arduino-compatible + Bluetooth Low Energy with built in USB plus battery charging
- Arduino IDE support
-  Cortex-M4 processor
- nRF52832 projects downward compatible
- Pre-programed the chip with our UF2 bootloader

### Install Adafruit nRF52 BSP via the Arduino Board Manager

1. Download and install the Arduino IDE (At least v1.6.12)
2. Start the Arduino IDE
3. Go into Preferences
4. Add https://www.adafruit.com/package_adafruit_index.json as an 'Additional Board Manager URL'
5. Restart the Arduino IDE
6. Open the Boards Manager from the Tools -> Board menu and install 'Adafruit nRF52 by Adafruit'
7. Once the BSP is installed, select 'Adafruit Bluefruit nRF52 Feather' from the Tools -> Board menu, which will update your system config to use the right compiler and settings for the nRF52.

## Hookup and Pins

### Power Pins

![Image](https://cdn-learn.adafruit.com/assets/assets/000/068/617/large1024/circuitpython_nRF52840_Power.png?1546459953)

- 3V: used to supply 3.3V power to external sensors, breakouts or Feather Wings
- LIPO Input (Bat):  Voltage supply from the optional rechargeable cell. Can be connected via JST PH connector.
- VREG Enable (En): Can be set to GND to disable the 3.3V output. By default set to HIGH.
- USB Power (USB): Supplies voltage from USB (4.5-5.2V)
