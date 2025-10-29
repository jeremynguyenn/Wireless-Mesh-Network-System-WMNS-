# Wireless-Mesh-Network-System-WMNS

<img width="1811" height="892" alt="image" src="https://github.com/user-attachments/assets/15cdb899-a5d3-4791-b68a-b0617ed99ad5" />

<img width="1837" height="894" alt="image" src="https://github.com/user-attachments/assets/e1832aeb-679c-49f6-9d0a-a94a7f7295fc" />

## Network Structure
This wireless mesh network is a proprietary, decentralized flood type network. The network consists of three distinct node types: routers (R), gateways (GT) and low-power end devices (LP).\
Routers retransmit received data to form the backbone of the network.\
Gateways are similar to routers and forward mesh network data to a server/cloud.\
End devices are low-power nodes that sleep for most of the time, periodically transmitting data.


<img width="507" height="544" alt="image" src="https://github.com/user-attachments/assets/d6db53ae-e917-4bbf-a5c9-d2c25314ba33" />


## Measured data
Currently, the following data is collected by the system through multiple sensor types (sensors in brackets, not necessarily utilized as such):
* Temperature (BME280, BME680, Si7021, SCD41, BMA400, mcu_internal)
* Relative humidity (BME280, BME680, Si7021, SCD41)
* Barometric pressure (BME280, BME680)
* Illuminance (OPT3001, VEML6030, Si1133/5)
* UV levels (Si1133/5)
* Sudden/discontinous motion (BMA400)
* Person counter (VL53L1X)
* CO2 concentration (SCD41)
* VOC concentration (BME680)
* Battery levels (ADC)
* Signal strength (radio)

## Custom Hardware Devices
GPSN             |  LRSN      |  CO2SN  | ALSN
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
<img src="https://github.com/jeremynguyenn/Wireless-Mesh-Network-System/blob/main/WMNS/Documentation/gpsn.png" alt="GPSN" width="150"/><br />General-purpose configurable sensor for: temperature, humidity, air pressure, light, VOCs, motion|<img src="https://github.com/jeremynguyenn/Wireless-Mesh-Network-System/blob/main/WMNS/Documentation/lrsn.png" alt="LRSN" width="200"/><br />Person counter sensor |  <img src="https://github.com/jeremynguyenn/Wireless-Mesh-Network-System/blob/main/WMNS/Documentation/co2sn.png" alt="CO2SN" width="200"/><br />Carbon dioxide concentration sensor | <img src="https://github.com/jeremynguyenn/Wireless-Mesh-Network-System/blob/main/WMNS/Documentation/alsn.png" alt="ALSN" width="200"/><br />Specialized light sensor for visible, UV, IR

GATEWAY             |  ROUTER32PA      |  ROUTER40  | LTSN | TERMINAL
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
<img src="https://github.com/jeremynguyenn/Wireless-Mesh-Network-System/blob/main/WMNS/Documentation/gateway.png" alt="GATEWAY" width="250"/><br />Internet gateway node  |<img src="https://github.com/jeremynguyenn/Wireless-Mesh-Network-System/blob/main/WMNS/Documentation/router32pa.png" alt="ROUTER32PA" width="150"/><br />Power amplified router node |  <img src="https://github.com/jeremynguyenn/Wireless-Mesh-Network-System/blob/main/WMNS/Documentation/router40.png" alt="ROUTER40" width="150"/><br />USB-powered router node |<img src="https://github.com/jeremynguyenn/Wireless-Mesh-Network-System/blob/main/WMNS/Documentation/ltsn.png" alt="LTSN" width="150"/><br />Specialized temp sensor for sub-zero|<img src="https://github.com/jeremynguyenn/Wireless-Mesh-Network-System/blob/main/WMNS/Documentation/terminal.png" alt="TERMINAL" width="150"/><br />Security node and gateway redundancy.
