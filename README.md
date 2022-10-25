# docker-compose-zigbee2mqtt

## About
A simple zigbee2mqtt docker container setup. 

## Configuration

### Docker
Example  docker configuration can be found in `.env.example`. Make a copy, name it `.env` and set the values to your needs. The only entry you need to change is the path to the Zigbee USB Adapter:

`USBADAPTER=/dev/ttyACM0`

### zigbee2mqtt
Example zigbee2mqtt configuration can be found in `volumes/app/data/configuration.example.yaml`. Maka a copy and name it `configuration.yaml`.
The only entry you need to change is the `mqtt.server`, where you set the url of the MQTT broker. 