# arduino_led_controller
An Arduino led controller for esp8266 using a web server

## How to use?
Well, it is so easy!

* Download this git repo
``` git pull https://github.com/Kwinnieprince/arduino_led_controller.git```
* Open the .ino file with your preffered arduino editor and edit the wifi ssid and password to your ssid and password.
* Flash the file to your esp8266 connect the serial console and see what IP-adress it gets from your dhcp-server.
  * When you want to have a static ip, assign it in your dhcp server to set it on a static ip address.
  
## Control lights or other things
* When you go to ```http://ip-address/on```, the esp will turn on GPIO pin 2
* When you go to ```http://ip-address/off```, the esp will turn off GPIO pin 2
* On the homepage ```http://ip-address```, you can see the status 1 for on and 0 for off
