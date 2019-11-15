# My Home as powered by Home Assistant

Since discovering Home Assistant in the summer of 2018, it has become my favorite hobby. 

Here are some screenshots of my configuration, the .yaml of which can be found in the files in this repo: 

<b> 1. The main page </b>

- a conditional card, with my currently open doors & windows
- a gauge card, which I use for humidity at the moment
- a graph card, which features the living room temperature
- the various rooms, with hardware such as:

  - ZWave power plugs (Fibaro)
  - ZWave flood sensors (Fibaro)
  - ZWave smoke sensor (Fibaro)
  - ZWave siren (Aeotec)  
  - ZWave window covers (Fibaro)
  - ZWave sensors for temperature, humidity, motion, light level (Fibaro & Aeotec)
  - Zigbee power plugs (IKEA Tradfri)
  - Zigbee light bulbs (Philips Hue, IKEA Tradfri)
  - Bluetooth LE presence detection (via Tile tags)
  - Bluetooth LE temperature & humidity sensors (Xiaomi Mijia)
  - Bluetooth LE plant sensor (Mi Flora)  
  - WiFi air quality sensor (Broadlink A1 for VOC)
  - WiFi air conditioning control via IR (Broadlink RM Mini)
  - WiFi light bulbs, light strip & desk lamp (Xiaomi Yeelight)
  - WiFi noise sensor (Broadlink A1)
  - WiFi thermostat and radiator valves (Netatmo) 
  
<img src="./images/1.1.png" width="1700">
<img src="./images/1.2.png" width="1700">

<b> 2. The camera page </b>

- most of the cameras are ONVIF standard, with PTZ
- a script turns them around to the wall based on presence detection, for privacy while in the house
- the REST platform is used for PTZ movements (cheap Chinese cameras, improperly supported at the moment) 
- the camera cards have buttons on them for position movement & presets

<img src="./images/2.png" width="1700">

<b> 3. The media player page </b>

- several Google Home Minis
- Chromecast Audio connected to home theater
- Chromecast Ultra connected to TV

<img src="./images/3.png" width="1700">

<b> 4. The "Today" page </b>

- WAQI sensor for city air quality
- moon phases
- local weather

<img src="./images/4.png" width="1700">

<b> 5. The System Administration page </b>

<img src="./images/5.1.png" width="1700">
<img src="./images/5.2.png" width="1700">

