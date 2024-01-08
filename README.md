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
  Check where node-red is install or not by this command:
  ```
    node-red
  ```
  Or you can start with this command also:
  ```
    node-red-start
  ```
  Now, open node-red and go to Manage Palette > Install section and install [node-red-contrib-dht-sensor](https://flows.nodered.org/node/node-red-contrib-dht-sensor) and [node-red-dashboard](https://flows.nodered.org/node/node-red-dashboard). 
- Code Implementation: Go to import section and import the code.
- Output: Go to browser and paste this url and you see a page where a graph and gauge for humidity and temperature.
  ```
    http://127.0.0.1:1880/weather-station
  ```
   
