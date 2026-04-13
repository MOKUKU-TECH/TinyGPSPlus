# TinyGPSPlus for ESP-IDF

A new, customizable Arduino NMEA parsing library
A *NEW* Full-featured GPS/NMEA Parser for Arduino
TinyGPSPlus is a new ESP-IDF library for parsing NMEA data streams provided by GPS modules.

update: Several pull requests incorporated (or equiv)
* Record the satellites detail states. [PR](https://github.com/yeliu-deepmirror/TinyGPSPlus/pull/1)
```
GPS 21 20 25 24 34 31 33 35 33
BeiDou 27 27 26 18 16 29 29 16 33 29 26 27 30
Galileo 33 29 32 32
GZSS 34 33 27 
```


Like its predecessor, TinyGPS, this library provides compact and easy-to-use methods for extracting position, date, time, altitude, speed, and course from consumer GPS devices.

However, TinyGPSPlus’s programmer interface is considerably simpler to use than TinyGPS, and the new library can extract arbitrary data from any of the myriad NMEA sentences out there, even proprietary ones.

See [Arduiniana - TinyGPSPlus](http://arduiniana.org/libraries/tinygpsplus/) for more detailed information on how to use TinyGPSPlus.
