# Arduino-home-thermostat-KT-013-DHT-TTGO-XI-WeMo-XI-Leonardo-Micro-Yún
Abbreviated for boards not able to hold all enhancements but needing KY-013 with calibration &amp;/or DHT.  Removed thermostat "auto" mode to make room while retaining "heat", "cool", and "off" thermostat modes.

If the ability to use KT-013 with calibration is more important to your application than the "auto" thermostat mode, this version will fit in boards with too little flash to hold both features together.  DHT11 and DHT22 are still supported. 

Note that in any case these boards still don't have enough flash to both initialize EEPROM and advance to production environment operation in the same compilation.  Be prepared to compile twice - once for EEPROM intitializing and the final time for production environment operation.

Read version v.0.9 README.md for full info in other respects.
