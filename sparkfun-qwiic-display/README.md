# sparkfun-qwiic-display
## 1. Description
- guide for how to use sparkfun oled display via I2C
## 2. Specimen
### 2-1. SSD1306 Display
[Official information about the display](https://www.smart-prototyping.com/blog/Zio-OLED-Display-Qwiic-Guide)
- Runs on 3.3V (when connected to arduino uno)
Two latter libraries will be installed automatically when you install the first one.
- [Adafruit_SSD1306](https://github.com/adafruit/Adafruit_SSD1306)
- [Adafruit GFX library](https://github.com/adafruit/Adafruit-GFX-Library)
- [Adafruit BusIO library](https://github.com/adafruit/Adafruit_BusIO)
### 2-2. Qwiic Micro OLED
[Hookup guide from Sparkfun](https://learn.sparkfun.com/tutorials/qwiic-micro-oled-hookup-guide?_ga=2.91923738.1483420915.1676386326-1508185197.1675351849) - also some Drawing Functions
- Runs on 3.3V
- [Micro OLED Breakout Library](https://github.com/sparkfun/SparkFun_Micro_OLED_Arduino_Library) - available at arduino library
- [qwiic micro oled](https://github.com/sparkfun/SparkFun_Qwiic_OLED_Arduino_Library) - available at arduino library -> use this one
### 2-2. Arduino Uno
- Black: GND
- Red: 3.3V
- Blue: Above AREF (2nd one on the right side of arduino)
- Yellow: Above blue (the first one on the right side of arduino)
### 2-3. Sparkfun Thing Plus
*Mine is not working right now: not detected*
- set as adafruit esp32 feather in IDE
- official guide: https://learn.sparkfun.com/tutorials/esp32-thing-plus-hookup-guide?_ga=2.158901946.1483420915.1676386326-1508185197.1675351849
## 5. Memo / Trial & Error
- 
