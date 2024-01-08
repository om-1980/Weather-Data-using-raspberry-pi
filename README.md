# Weather-Data-using-raspberry-pi
A Raspberry Pi weather station is a DIY project that combines the affordability and versatility of the Raspberry Pi with various sensors to collect and analyze weather data. This project is suitable for hobbyists, students, and weather enthusiasts who want to create a personalized weather monitoring system.

# Components:
- Raspberry Pi
- DHT22 Sensor
- Jumper Wires
- Breadboard


# Setup Steps:
- Hardware Assembly: Connect the weather sensors(DHT22) Raspberry Pi to GPIO4.
- Software Installation: Install the Raspbian operating system on the Raspberry Pi and set up node-red.
  ```
    sudo npm install -g --unsafe-perm node-red
  ```
  Check where node-red is installed or not by this command:
  ```
    node-red
  ```
  Or you can start with this command also:
  ```
    node-red-start
  ```
  Now, open node-red and go to Manage Palette > Install section and install [node-red-contrib-dht-sensor](https://flows.nodered.org/node/node-red-contrib-dht-sensor) and [node-red-dashboard](https://flows.nodered.org/node/node-red-dashboard). 
- Code Implementation: Go to the import section and import the code.
- Output: Go to the browser and paste this URL and you will see a page with a graph and gauge for humidity and temperature.
  ```
    http://127.0.0.1:1880/weather-station
  ```
  And for only checking sensor data got to
  ```
    http://127.0.0.1:1880/sensorReadings
  ```
# Circuit Diagram
![circuit ](https://github.com/om-1980/Weather-Data-using-raspberry-pi/assets/111452597/b86ddf1d-a073-4b7d-aa39-fb36f942de8c)

# Output window
![output](https://github.com/om-1980/Weather-Data-using-raspberry-pi/assets/111452597/b63516d4-472e-4cb0-92a0-37cab896a183)
![Output1](https://github.com/om-1980/Weather-Data-using-raspberry-pi/assets/111452597/0751dab9-3aa5-4d60-bb35-8fa6b6c9833a)

