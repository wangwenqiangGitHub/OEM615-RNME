# OEM615-RNME
Raw Navigation Message Extraction from OEM615 Reciever Log File, including GPS, BDS, GLO.

Only test it in Windows. 

## OEM615 Reciever Log Type Selection
- GPS: RAWGPSWORD
- BDS: BDSRAWNAVSUBFRAME
- GLO: GLORAWSTRING

## OEM615 Reciever Log File Suffix Change
U must chang the log file suffix as one of below.

- GPS: .gps
- BDS: .bds
- GLO: .glo
- MIX: .mix (with some of above)

## Default Configuration File
RNME.conf

## Usage
./Nav_Trans.exe [config file (option)]

The default config file --> RNME.conf, u can change by yourself.

Executable file and the default config file shoude be put in same dir.

**example:**  
./Nav_Trans.exe 

./Nav_Trans.exe test.conf

## Result Files
- GPS: GPSNAV.txt
- BDS: BDSNAV.txt
- GLO: GLONAV.txt

**example:**  prn#raw_nav_bin
```
14#000011010010110000001011101110
22#000011000101010001111010001001
25#010000101100110001111101000000
```


