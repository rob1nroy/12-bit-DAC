## 12-bit-DAC

# 1.Purpose of Digital to Analog Converter (DAC)
In real world, most of the data available is in the form of analog in nature. We have two types of converters analog to digital converter and digital to analog converter. These two converting interfaces are essential to obtain the required operations of a processor to manipulate the data of digital electronic equipment and an analog electric equipment. Digital to Analog Converter (DAC) is a device that transforms digital data into an analog signal in order to interact with the real world. The digital signal is represented with a binary code, which is a combination of bits 0’s and 1’s. The digital data can be produced from a microprocessor, Field Programmable Gate Array (FPGA), or Application Specified Integrated Circuit (ASIC). There are two commonly used DAC conversions – Weighed resistors method and R-2R ladder network method. Applications of a DAC: audio amplifier, video encoder, display electronics, data acquisition systems, calibration, Digital potentiometer.

# 2.Block Diagram

![Block Diagram](https://user-images.githubusercontent.com/79626421/166171500-2858aaa8-d1ea-4c15-9f12-83ce8cd7e88c.jpeg)
# Terminal Functions

| Name | Pin No | I/O | Description |
| :---         |     :---:      |     :---:      |           :--- |
| B[0:11]   | 1-12   |I  | Digital Inputs    |
| EN     | 13       |I| Enable Pin      |
| VCC     | 14      |I | Digital Power Supply (1.6)     |
| GND     | 15      |I| Digital Ground      |
| OUT    | 16       |O| DAC analog voltage output     |
| VDDA     | 17       |I| Analog voltage supply (3.3)     |
| VSSA     | 18       |I| Analog Ground      |
| VREFH     | 19    |I  | Reference voltage high for DAC (3.3)     |
| VREFL    | 20  | I    | Reference voltage low for DAC      |

# 3.Implementation of 12Bit R2R DAC
![12Bit R2R DAC](https://user-images.githubusercontent.com/79626421/166172803-d0a349eb-651f-4b2c-8563-5999231a9f52.jpg)

# 4.Contributors
- Robin Roy, BTech in Electronics and Communication, Amal Jyothi College of Engineering, Kerala, India; Contact: (robinroy@ieee.org)
- Richu Bini, BTech in Electronics and Communication, Amal Jyothi College of Engineering, Kerala, India; Contact: (richubini101@gmail.com)
- Reno S Kurisinkal, BTech in Electronics and Communication, Amal Jyothi College of Engineering, Kerala, India; Contact: (renoskurisinkal.tech@gmail.com)
