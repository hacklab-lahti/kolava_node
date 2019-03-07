# kolava_node
Ventilation node

Ventilation valve control for ESP32 with MicroPython firmware.

Uses umqtt library (https://github.com/micropython/micropython-lib/tree/master/umqtt.simple)

1. Flash micropython firmware to your ESP32
2. Rename settings-example.json to settings.json and modify at least wifi and mqtt server settings.
3. Upload files to ESP32 with adafruit-ampy