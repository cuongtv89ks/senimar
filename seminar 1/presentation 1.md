# Seminar 1

content

1. Arduino
  - Advantages
  - Disadvantage
  - How to take the best Advantages
2. Some important Protocols/ Communications
  - UART
  - I2C/TWI
  - SPI
  - USB
3. Altium Designer
***


## 1. Arduino
>It is an open-source electronics prototyping platform based on flexible, easy to use hardware and software
***

### Advantages
1. Hardware side you are all set at least for core section, you have to only connect your selected external devices such as i/o devices.
2. Lots of support over the web and offline avaiable
3. No need to create own functions as well as libraties for peripherals. Most of them are inbuilt and demo projects already give in IDE, so no need to download samples even.
4. No need to use USB to serial coverter for Data transfer with PC. Because it has inbuilt USB Serial chip, which is not provided in most of other devices out of the box.
5. No need of external programmer. This is the best feature.
6. As is is opensource in nature so if you are not willing to pay huge amount for original one, then you also buy the clones which are manufactured by vendors in your own country. These boards costs only about 40% of original one, yet fully compatible.
***

### Disadvantage

1. Arduino program actually using C/C++ program with closed library. You can not look into a function to know what is inside and how the MicroController worked. The reason is their purpose that they want you buy only their products. And when you change another MCU, it will be stucked here.
2. For newbie, if you just use Arduino's library then it is difficult to understand how the hardware worked, the registers are set, how the communications (SPI, I2C, UART, ...), timmer, interrupter worked. Then you just do the API, not actually like Electrics Engineer.
3. Arduino IDE is poor.
4. Sometimes using Arduino's library will waste your microprocessor's memory.
	For simple example using my own UART to write "Hello world" code on Atmega328p 		(Arduino is using):

    `Program Memory Usage: 312 bytes 1.1% Full`
    `Data Memory Usage: 66 bytes 2.2% Full`

    With Arduino:
    `Program Memory Usage: 3.230 Kb 10% Full`
    `Data Memory Usage: 329 bytes 16% Full`
***

### How to take the best advantage

Then I change Arduino IDE to [Atmel Studio 7](http://www.atmel.com/Microsite/atmel-studio/) to build my own library and project. Then how to upload the hex file to Arduino? Fortunately, there are one program can do. That is [Xload ](https://github.com/cuongtv89ks/avr/tree/master/XLoader).
***

## 2. Some important Protocols/Communications
  - UART
  - I2C/TWI
  - SPI
  - USB
***

### UART
***

### I2C/TWI
***

### SPI
***

### USB
***

## 3. Altium Designer
