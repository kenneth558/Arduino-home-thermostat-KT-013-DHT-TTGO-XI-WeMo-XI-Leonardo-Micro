# Use of KY-013 almost supported, but not yet

# Arduino-home-thermostat-KT-013-DHT-TTGO-XI-WeMo-XI-Leonardo-Micro-Yún
For all boards, but compiles smaller in those boards without room for the thermostat auto mode option but need the other enhancements including KY-013 with calibration &amp;/or DHT.  In boards needing it, the thermostat "auto" mode option is skipped to make room. "heat", "cool", and "off" thermostat mode options are retained. In boards with good capacity, all enhancements remain.  This version will be the base version for all future versions and will include future enhancements that compile only for boards that they will fit in.

If the ability to use KT-013 with calibration is more important to your application than the "auto" thermostat mode, this version will fit in boards with too little flash to hold both features together.  DHT11 and DHT22 are still supported. 

Note that in any case these boards still don't have enough flash to both initialize EEPROM and advance to production environment operation in the same compilation.  Be prepared to compile twice - once for EEPROM intitializing and the final time for production environment operation.

Read version v.0.9 README.md for full info in other respects.
