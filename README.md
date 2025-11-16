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
<img src="https://github.com/user-attachments/assets/f54c3141-ba1e-4432-a529-c9a74645f79c" alt="GPSN" width="150"/><br />General-purpose configurable sensor for: temperature, humidity, air pressure, light, VOCs, motion|<img src="https://github.com/user-attachments/assets/5cc3a9ba-3a54-4b9a-add4-47e679b32061" alt="LRSN" width="200"/><br />Person counter sensor |  <img src="https://github.com/user-attachments/assets/c826942c-8c65-4fe7-afed-26d54490e5c3" alt="CO2SN" width="200"/><br />Carbon dioxide concentration sensor | <img src="https://github.com/user-attachments/assets/009889b2-56bc-4779-81d9-b329df332afb" alt="ALSN" width="200"/><br />Specialized light sensor for visible, UV, IR

GATEWAY             |  ROUTER32PA      |  ROUTER40  | LTSN | TERMINAL
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
<img src="https://github.com/user-attachments/assets/1b343f34-c2f3-4710-b77d-e93d2db9315e" alt="TERMINAL" width="150"/>

<img src="https://github.com/user-attachments/assets/09a26ce3-26dd-4dcb-88a6-f8af419129de" alt="GATEWAY" width="250"/><br />Internet gateway node  |<img alt="image" src="https://github.com/user-attachments/assets/abbb71bb-6450-4114-a7c5-42e90e79dc92" alt="ROUTER32PA" width="150"/><br />Power amplified router node |  <img src="https://github.com/user-attachments/assets/4b4c8670-44cc-470e-924c-278914f1e0db" alt="ROUTER40" width="150"/><br />USB-powered router node |<img src="https://github.com/user-attachments/assets/ecd05519-1ffc-4b67-a8d1-8f133ec4eb0f" alt="LTSN" width="150"/><br />Specialized temp sensor for sub-zero|<img src="https://github.com/user-attachments/assets/1b343f34-c2f3-4710-b77d-e93d2db9315e" alt="TERMINAL" width="150"/><br />Security node and gateway redundancy.
