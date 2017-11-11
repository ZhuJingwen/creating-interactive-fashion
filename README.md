# creating-interactive-fashion

This is a collection of code examples for workshop Creating Interactive Fashion.

### Workshop Description
- This workshop provides an introductory experience in the techniques, materials and basic knowledge of fashion technology. Consider this class your lab for experimentation and sample production.

### Gemma M0 Setup
[https://learn.adafruit.com/adafruit-gemma-m0/arduino-ide-setup](https://learn.adafruit.com/adafruit-gemma-m0/arduino-ide-setup)

#### Windows
- [Install Adafruit Windows Driver](https://learn.adafruit.com/getting-started-with-flora/windows-setup)
- [Download Arduino](https://www.arduino.cc/en/Main/Software)
- [Install Adafruit Boards Support](https://learn.adafruit.com/adafruit-arduino-ide-setup/arduino-1-dot-6-x-ide)
	- Arduino File Manu >> Preferences
	- Paste

	https://adafruit.github.io/arduino-board-index/package_adafruit_index.json

	into the "Additional Board Managers URLS" box
	- Click OK to save the new preference settings
	- Arduino Tools Manu >> Board >> Boards Manager
	- Search **Adafruit AVR Boards**
	- Click Install
	- Search **Adafruit SAMD Boards**
	- Click Install
	-  After installing, quit and reopen the Arduino IDE to ensure that all of the boards are properly installed. You should now be able to see the new boards listed in the Tools->Board menu.

#### Mac
- [Download Arduino](https://www.arduino.cc/en/Main/Software)
- [Install Adafruit Boards Support](https://learn.adafruit.com/adafruit-arduino-ide-setup/arduino-1-dot-6-x-ide)
	- Arduino >> Preferences
	- Paste https://adafruit.github.io/arduino-board-index/package_adafruit_index.json into the "Additional Board Managers URLS" box
	- Click OK to save the new preference settings
	- Arduino Tools Manu >> Board >> Boards Manager
	- Search **Arduino SAMD Boards**
	- Click Install
	- Search **Adafruit SAMD Boards**
	- Click Install
	-  After installing, quit and reopen the Arduino IDE to ensure that all of the boards are properly installed. You should now be able to see the new boards listed in the Tools->Board menu.

#### Linux
- [Setup](https://learn.adafruit.com/adafruit-arduino-ide-setup/linux-setup)


### Flora Neopixels
 - [Library](https://learn.adafruit.com/adafruit-neopixel-uberguide/arduino-library-installation)
 - Arduino >> Sketch >> Include Library >> Manage Libraries
 - Search **Neopixel**
 - Find **Adafruit Neopixel**
 - Click Install
