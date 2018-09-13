# Unit Converter
Unit Conversion Add-In for Excel 2016.

## Installation / Setup
For full installation details, please download and follow the user guide.

Alternatively for quickstart, see below:
 - Download the latest release from this repository
 - Save the .xla file to your preferred location
 - Open Excel and import the Add-in

## Usage
For full usage details, please download and follow the user guide.

Alternatively for quickstart, see below:
- In an excel cell, type '=conv'. Excel will bring up a suggested list of functions.
  All functions are setup as 'convXXX' where XXX represents the unit type to be converted. E.g. ConvPressure.

- The function is setup as convXXX(Value to be converted , Unit to convert from , Unit to convert to).
  For example =convTemperature(10,"C","K") would convert 10 degrees to Kelvin.

- To see a list of avaliable units for any function, use =convHelp('Function Name')
  Note that Function name is the name of the function minus 'conv' at the start
  E.g =convHelp("Pressure") would list all pressure units
  
- Its noted that pressure units are prefixed by (a) or (g) to represent absolute or gauge.
  This is very useful when used in conjunction with the REFPROP excel functions.
  E.g. =convPressure(10,"bar(a)","psi(g)")
