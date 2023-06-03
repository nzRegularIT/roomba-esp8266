# roomba-esp8266

## Name
Controlling the Roomba 600 series with Home Automation

## Introduction
I was lucky enough to be given a Roomba 630, and while this old robot does a great job of cleaning, it has no smarts! Of course I could actually go out and buy one with thousands of sensors and Wifi, but where is the fun if you can't hack it yourself?

Being my first project in adding WiFi to a device, I got caught in plenty of hurdles. I found a number of articles for programming an ESP8266 showing a breadboard, a handful of components and jumper cables. I purchased from a local supplier a number of items including an ESP-01 ESP8266, a USB FTDI USBto TTL Serial Adapter, a breadboard power supply and components. I spent hours lost in articles that assume you have some sort of knowledge of how to program an ESP8266, trying to get the AT commands to work. It wasn't until a friend lent me an ESP programming board and pointed me to the Arduino IDE that I finally figured a few things out.

1. You have no idea what firmware might arrive on your ESP8266
2. Invest in an ESP programming board, it will save you hours of sanity!

## The ESP8266
Once I hooked the ESP8266 up to the programming board, things become much easier! I was able to plug the USB port into my machine, no drivers required, COM port was there, and I could load up a basic program!

### Programming board
Find one from AliExpress, search for "esp8266 test frame burner"

### Arduino IDE
1. Download Arduino IDE.
2. Open you IDE and click on "File -> Preferences".
3. In  "Aditional Boards Manager URLs" add this line and click on "OK": http://arduino.esp8266.com/stable/package_esp8266com_index.json
4. Go to "Tools -> Board -> Boards Manager", type "ESP8266" and install it.
5. Go againt to "Tools -> Board" and select "Generic ESP8266 Module".


## Installation
1. Install Home Automation
2. Install MQTT

## Usage
Use examples liberally, and show the expected output if you can. It's helpful to have inline the smallest example of usage that you can demonstrate, while providing links to more sophisticated examples if they are too long to reasonably include in the README.

## Support
Tell people where they can go to for help. It can be any combination of an issue tracker, a chat room, an email address, etc.

## Roadmap
If you have ideas for releases in the future, it is a good idea to list them in the README.

## Contributing
State if you are open to contributions and what your requirements are for accepting them.

For people who want to make changes to your project, it's helpful to have some documentation on how to get started. Perhaps there is a script that they should run or some environment variables that they need to set. Make these steps explicit. These instructions could also be useful to your future self.

You can also document commands to lint the code or run tests. These steps help to ensure high code quality and reduce the likelihood that the changes inadvertently break something. Having instructions for running tests is especially helpful if it requires external setup, such as starting a Selenium server for testing in a browser.

## Authors and acknowledgment
https://help.ubidots.com/en/articles/928408-program-the-esp8266-with-the-arduino-ide-in-3-simple-steps

## License
For open source projects, say how it is licensed.

## Project status
If you have run out of energy or time for your project, put a note at the top of the README saying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.
