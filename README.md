# aqi
Measure AQI based on PM2.5 or PM10 with a Raspberry Pi and a SDS011 particle sensor

## Getting Started

You will require the following parts:
 * Raspberry Pi 3B+
 * SDS011 PM2.5 PM10 Particle Sensor
 
Attach the SDS011 USB-Serial converter to the Raspberry Pi USB Port.

Clone the repository onto the Raspberry Pi.

`$ git clone https://github.com/wallarug/aqi `

Change into the cloned repository directory:

`$ cd aqi `

Make the aqi.py file executable

`$ chmod +x aqi.py `

Run the python script

`$ python aqi.py `

...or in the background

`$ python aqi.py & `
