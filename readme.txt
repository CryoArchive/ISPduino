ISPduino

The ISPduino is an Arduino based board meant to minimize the number of components and integrate easily with your prototyping needs. The digital and analog IO pins are identical to the Arduino so programming with the Arduino IDE is easily integrated into your project.

The board is designed to be programmed using and AVR ISP programmer. 

ISPduino_1sided: The single sided board is unfortunately designed for ease of use into my own projects, the pinout for the ISP programmer is listed below. There are only four pins meaning there are no pins for VCC and GND. (I found that my programmer did not provide sufficient power to run the controller.) 

- MOSI
- RESET
- SCK
- MISO

ISPduino_2sided: The double sided board is designed more for the consumer and contains two PCB layouts in the folder. The first layour is just a standard copy. The second is the same thing just with a board layout ready for submission to the OSHpark.com pcb fabrication system. The second version is for a 2"x2" board which will get you 6 boards at $10. The ISP pinout is the standard 6pin connection, where the square pad is pin 1.