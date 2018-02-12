[![ MCP9805](MCP9805_I2C.png)](https://store.ncd.io/product/mcp9805-memory-module-digital-temperature-sensor-%C2%B11c-at-75c-to-95c-i2c-mini-module/).

#  MCP9805

The MCP9805 is a temperature sensor and a memory module designed to meet the JEDEC for Mobile Platform Memory Module Thermal Sensor.This device provides an accuracy of ±1°C from a temperature range of +75°C to +95°C. The MCP9805 comes with user-programmable registers that provide flexibility for dual in-line memory module (DIMM) temperature-sensing applications.
This Device is available from www.ncd.io 

[SKU: MCP9805]

(https://store.ncd.io/product/mcp9805-memory-module-digital-temperature-sensor-%C2%B11c-at-75c-to-95c-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface MCP9805 memory module and temperature sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/mcp9805-memory-module-digital-temperature-sensor-%C2%B11c-at-75c-to-95c-i2c-mini-module/">MCP9805 memory module and temperature sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python MCP9805.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
