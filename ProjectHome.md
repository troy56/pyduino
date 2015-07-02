## About ##
pyduino is a library which allows you to communicate with [Arduino](http://www.arduino.cc/) boards loaded with the [Firmata](http://firmata.org/) protocol from within Python.  It currently supports version 2 of the Firmata protocol.

## Dependencies ##
[pySerial](http://pyserial.wiki.sourceforge.net/pySerial)

## Usage ##
See [example.py](http://code.google.com/p/pyduino/source/browse/trunk/example.py) for an example of pyduino being used to perform analog and digital i/o.

## Caveats ##
The library has not been extensively tested with Firmata V2, and as such should be considered alpha quality.  Also the API is a little messy at the moment, especially its handling of digital ports, and so is liable to change at some point.