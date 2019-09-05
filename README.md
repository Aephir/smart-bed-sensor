# smart-bed-sensor
DIY Smart Bed using Load Cells and HX711 (https://selfhostedhome.com/diy-bed-presence-detection-home-assistant/). 
Above guide didn't work completely, but with new PubSubClient and a few edits (implemented in this repo) it works.

See http://www.arjunsk.com/iot/esp8266-programming-cloud-mqtt-part-3/ and https://techtutorialsx.com/2017/04/09/esp8266-connecting-to-mqtt-broker/ for more examples for new PubSubClient.

For dummies (using PlatformIO in atom editor):

1. Edit the `.../src/config.h`, add wifi SSID and password, along with IP:port of your MQTT broker, state topics, etc.
  a. pins:
2. Open a new PlatformIO terminal and navigate to your project.
3. Run `./build_and_deploy.sh`

When defining pins in config.h, use the GPIO#:
- D0 = 16
- D1 =  5
- D2 =  4
- D3 =  0
- D4 =  2
- D5 = 14
- D6 = 12
- D7 = 13
- D8 = 15

See [this overview](https://www.instructables.com/id/NodeMCU-ESP8266-Details-and-Pinout/).
