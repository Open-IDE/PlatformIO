# Upload Port
PlatformIO automatically detects upload port by default. You can configure a custom port using upload_port option in platformio.ini:
- upload_port = COM1 - particular port
- upload_port = /dev/ttyUSB* - any port that starts with /dev/ttyUSB
- upload_port = COM[13] - COM1 or COM3.
