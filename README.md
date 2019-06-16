# smart-bed-sensor
DIY Smart Bed using Load Cells and HX711 (https://selfhostedhome.com/diy-bed-presence-detection-home-assistant/)

For dummies (using PlatformIO in atom editor):

1. Edit the `.../src/config.h`, add wifi SSID and password, along with IP:port of your MQTT broker, state topics, etc.
  a. pins:
2. Open a new PlatformIO terminal and navigate to your project.
3. Run `./build_and_deploy.sh`
