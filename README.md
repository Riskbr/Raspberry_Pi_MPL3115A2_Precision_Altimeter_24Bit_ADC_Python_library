[![ MPL3115A2](MPL3115A2_I2C.png)](https://store.ncd.io/product/mpl3115a2-precision-altimeter-with-24-bit-analog-to-digital-converter-i2c-mini-module/).

#  MPL3115A2

Freescale’s MPL3115A2 employs a MEMS pressure sensor with an I2C interface to provide accurate Pressure/Altitude and Temperature data.The sensor outputs are digitized by a high resolution 24-bit ADC. It is capable of detecting a change in only 0.05 kPa which equates to a 0.3m change in altitude.
This Device is available from www.ncd.io 

[SKU: MPL3115A2]

(https://store.ncd.io/product/mpl3115a2-precision-altimeter-with-24-bit-analog-to-digital-converter-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface MPL3115A2 altimeter and 24bit ADC With Raspberry Pi :
1. <a href="https://store.ncd.io/product/mpl3115a2-precision-altimeter-with-24-bit-analog-to-digital-converter-i2c-mini-module/">MPL3115A2 altimeter and 24bit ADC</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python MPL3115A2.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
