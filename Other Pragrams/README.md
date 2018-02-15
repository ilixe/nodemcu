python esp8266/luatool/luatool.py --port /dev/ttyUSB0 --src init.lua --dest init.lua --restart


sudo python esp8266/luatool/luatool.py --delay 0.6 --port /dev/ttyUSB0 --src init.lua --dest init.lua --restart  --verbose

to write firmware of lua
sudo /home/godfather/.local/bin/esptool.py --port /dev/ttyUSB1 write_flash -fm=dio -fs=32m 0x00000 nodemcu-master-8-modules-2017-07-02-06-47-31-integer.bin
