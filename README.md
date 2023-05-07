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



## Badges
On some READMEs, you may see small images that convey metadata, such as whether or not all the tests are passing for the project. You can use Shields to add some to your README. Many services also have instructions for adding a badge.

## Visuals
Depending on what you are making, it can be a good idea to include screenshots or even a video (you'll frequently see GIFs rather than actual videos). Tools like ttygif can help, but check out Asciinema for a more sophisticated method.

## Installation
Within a particular ecosystem, there may be a common way of installing things, such as using Yarn, NuGet, or Homebrew. However, consider the possibility that whoever is reading your README is a novice and would like more guidance. Listing specific steps helps remove ambiguity and gets people to using your project as quickly as possible. If it only runs in a specific context like a particular programming language version or operating system or has dependencies that have to be installed manually, also add a Requirements subsection.

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
Show your appreciation to those who have contributed to the project.

## License
For open source projects, say how it is licensed.

## Project status
If you have run out of energy or time for your project, put a note at the top of the README saying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.
