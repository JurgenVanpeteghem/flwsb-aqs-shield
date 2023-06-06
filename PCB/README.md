
# Air quality sensor shield

# PCB
For the project we made a seperate sensorboard wich contains all the sensors we use for the projetc. The purpose of this connector board is to connect all sensors to the main FLWSB. The FLWSB can collect the data drom the sensors on this board and send this data over lorawan.

The board contains following sensors to measure differnent parameters of airquality: 
  - BME280 (relative humidity- and tamperature 3,3V - I2C)
  - SGP41 (VOC en NOx sensor 3,3V - I2C)
  - SCD41 (CO2 sensor 3,3V - I2C)
  - Jst-connector for SPS30 (particulate matter sensor 5V - I2C)

additionally some pinheaders where added to connect a GY-NEO6MV2 GPS module and a solar power manager board to provide solar power to the board.

![Connectorboard](assets/connectorboard.png 'Figuur 1: Connectorboard')

![Connectorboard](assets/connectorboard1.jpg 'Figuur 2: Connectorboard1')

To solder the SMD sensors to the board solder paste was applied to the pads on the PCB. Then we soldered the sensors with a reflow oven. To get the sensors to work, we had to put some boards a second time in the reflow oven.

# Bill of materials
| Component  | amount  |
|---|---|
| 15 pin header female | 2 |
| 4 pin header male | 2 |
| SPS30 JST 5 pin connector | 1 |
| SDC41 | 1 |
| SGP41 | 1 |
| BME280 | 1 |
| capacitor 1µF  | 2  |
| capacitor 100nF  | 4  |
| resistor 4,7Ω  | 1  |
