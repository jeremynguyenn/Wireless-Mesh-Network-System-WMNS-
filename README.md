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
