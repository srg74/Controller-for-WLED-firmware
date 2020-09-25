[![](https://img.shields.io/github/v/release/srg74/Controller-for-WLED-firmware)](https://img.shields.io/github/v/release/srg74/Controller-for-WLED-firmware)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://github.com/srg74/Controller-for-WLED-firmware/master/LICENSE)
[![](https://img.shields.io/static/v1?label=Localized&message=firmware&color=blue&style=flat-square)](/resources/FIRMWARE/BIN)
[![](https://img.shields.io/static/v1?label=WLED&message=firmware&color=green&style=flat-square)](https://github.com/Aircoookie/WLED/releases)
[![](https://img.shields.io/static/v1?label=WLED&message=app&color=green&style=flat-square)](https://github.com/Aircoookie/WLED-App)

I appreciate your support for my project! [![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=VU7L89Z2RR7S4&source=url)

## Wi-Fi LED controller based on ESP-07S module with external antenna for WLED firmware.
![Controller](resources/controller.jpg)
```
Controller reference design
```
![Test](resources/PCB_test.jpg)
```
PCB test v0.8
```
## Wi-Fi LED controller with following features
-   Easy to solder components;
-   Relay for reducing delay power consuption;
-   Waterproof enclosure IP67;
-   Level shifter for relaible signal;
-   Power selector (e.g 5VDC or 12VDC);
-   Serial interface connector 3.3V logic levels;
-   IR receiver (optional);
-   SSD1306 I2C OLED display 128x32 or 128x64 (optional);
-   Additional button (optional);
-   Dallas temperature sensor for measuring ambient temperature inside of enclosure (optional);
-   [PCB ORDER](https://www.pcbway.com/project/shareproject/Controller_for_WLED_firmware_in_waterproof_enclosure.html) - Easy and fast way to order quality PCB.
-   [Sign in and save](https://www.pcbway.com/setinvite.aspx?inviteid=83580) - Helping me to save some money for development.

## Firmware used
-   [WLED repository](https://github.com/Aircoookie/WLED) - Main WLED repository
-   [Usermod files](https://github.com/Aircoookie/WLED/tree/master/usermods/Enclosure_with_OLED_temp_ESP07) - Folder with required changes to usermod.cpp in WLED repository
-   [Controller firmware](https://github.com/srg74/Controller-for-WLED-firmware/tree/master/resources/FIRMWARE) - Custom build file, ready for upload. Latest Build 2004061.
## Materials used
-   [Enclosure](https://www.hawkusa.com/manufacturers/bud/enclosures/pn-1321-cmb) - Bud Industries PN-1321-CMB
-   [Connection](https://www.amazon.com/dp/B07Q6XK8KM/ref=cm_sw_em_r_mt_dp_U_P6gQEb3590DWJ) - Waterproof IP65 2pin and 3pin connection cables
-   [Box entry](https://www.amazon.com/dp/B06Y5HGYK2/ref=cm_sw_em_r_mt_dp_U_n9gQEb0NFN1HF) - Cable gland PG7
-   [ESP-07S module](https://www.amazon.com/gp/product/B07KRZWZQV/ref=ppx_yo_dt_b_asin_title_o00_s02?ie=UTF8&psc=1) - ESP8266 based ESP-07S module with external antenna
-   [Wi-Fi antenna](https://www.amazon.com/gp/product/B00ZBJNO9O/ref=ppx_yo_dt_b_asin_title_o08_s00?ie=UTF8&psc=1) - 2.4G WiFi Antenna with SMA Cable 3DBI Gain
-   [Push button](https://www.newark.com/philmore/30-12638/switch-operation-momentary-spring/dp/43W7758) - Pushbutton Switch with LED. Manufacturer #30-12638
-   [Custom PCB](https://www.pcbway.com) - Custom PCB ordered from PCBway. 10pcs for $5!
-   [BOM for PCBs](https://github.com/srg74/Controller-for-WLED-firmware/blob/master/resources/) - Here is BOM for controller. PLEASE REFFER TO YOUR BUILD!
#### Board creation is inspired by https://github.com/Aircoookie/WLED/wiki
