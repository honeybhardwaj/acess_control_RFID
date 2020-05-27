# Acess_Control_RFID
automatic door lock system using rfid module and arduino

# INTRODUCTION
The project that we have made is an RFID door lock at an affordable price. The goal of this project is to create a more convenient way to unlock your door than the traditional key. In the key’s place is an RFID tag that will unlock the door by proximity. However, the improvements of this RFID door lock must outweigh the complications of implementation.
The design consists of two components. The first component is the actual door lock that must be installed in the doorframe. This will be controlled by a magnetic lock and will need to be powered. The second component is a relatively small module that you can install anywhere near the door. This module is responsible for RFID sensing.

# What is RFID?
RFID stands for Radio Frequency Identification
RFID a non-contact technology that’s broadly used in many industries for tasks such as personnel tracking, access control, supply chain management, books tracking in libraries, tollgate systems and so on.
# Working
An RFID system consists of two main components, a transponder or a tag which is located on the object that we want to be identified, and a transceiver or a reader.
The RFID reader consists of a radio frequency module, a control unit and an antenna coil which generates a high-frequency electromagnetic field. On the other hand, the tag is usually a passive component, which of just an antenna and an electronic microchip, so when it gets near the electromagnetic field of the transceiver, due to induction, a voltage is generated in its antenna coil and this voltage serves as power for the microchip. Now as the tag is powered it can extract the transmitted message from the reader, and for sending the message back to the reader, it uses a technique called load manipulation. Switching on and off a load at the antenna of the tag will affect the power consumption of the reader’s antenna which can be measured as voltage drop. This changes in the voltage will be captured as ones and zeros and that’s the way the data is transferred from the tag to the reader.

# What is ARDUINO?
➢ The Arduino UNO is an open-source microcontroller board based on the Microchip ATmega328P microcontroller and developed by Arduino.cc. The board is equipped with sets of digital and analog input/output (I/O) pins that may be interfaced to various expansion boards (shields) and other circuits.
➢ The board has 14 Digital pins, 6 Analog pins, and programmable with the Arduino IDE (Integrated Development Environment) via a type B USB cable. It can be powered by a USB cable or by an external 9-volt battery, though it accepts voltages between 7 and 20 volts. It is also similar to the Arduino Nano and Leonardo.
➢ The hardware reference design is distributed under a Creative Commons Attribution Share-Alike 2.5 license and is available on the Arduino website. Layout and production files for some versions of the hardware are also available. "Uno" means one in Italian and was chosen to mark the release of Arduino Software (IDE) 1.0.
➢ The Uno board and version 1.0 of Arduino Software (IDE) were the reference versions of Arduino, now evolved to newer releases. The Uno board is the first in a series of USB Arduino boards and the reference model for the Arduino platform. The ATmega328 on the Arduino Uno comes preprogrammed with a bootloader that allows uploading new code to it without the use of an external hardware programmer. It communicates using the original STK500 protocol. The Uno also differs from all preceding boards in that it does not use the FTDI USB-to-serial driver chip. Instead, it uses the Atmega16U2 programmed as a USB-to-serial converter.

# LCD MODULE
LCD modules are very commonly used in most embedded projects, the reason being its cheap price, availability and programmer friendly. Most of us would have come across these displays in our day to day life, either at PCO’s or calculators. The appearance and the pinouts have already been visualized above now let us get a bit technical. 16×2 LCD is named so because; it has 16 Columns and 2 Rows. There are a lot of combinations available like 8×1, 8×2, 10×2, 16×1, etc. but the most used one is the 16×2 LCD. So, it will have (16×2=32) 32 characters in total and each character will be made of 5×8 Pixel Dots.

# SERVO MOTOR
A servo motor is an electrical device which can push or rotate an object with great precision. If you want to rotate an object at some specific angles or distance, then you use a servo motor. It is just made up of a simple motor which runs through a servo mechanism. If the motor is used is DC powered then it is called DC servo motor, and if it is AC powered motor then it is called an AC servo motor. We can get a very high torque servo motor in a small and lightweight package. Due to these features, they are being used in many applications like a toy car, RC helicopters, and planes, Robotics, Machine, etc.
Servo motors are rated in kg/cm (kilogram per centimeter) most hobby servo motors are rated at 3kg/cm or 6kg/cm or 12kg/cm. This kg/cm tells you how much weight your servo motor can lift at a particular distance. For example, A 6kg/cm Servo motor should be able to lift 6kg if the load is suspended 1cm away from the shaft of the motor, the greater the distance the lesser the weight carrying capacity.
The position of a servo motor is decided by an electrical pulse and its circuitry is placed beside the motor.

# IR Sensor
An infrared sensor is an electronic device, that emits in order to sense some aspects of the surroundings. An IR sensor can measure the heat of an object as well as detects the motion. These types of sensors measure only infrared radiation, rather than emitting it that is called a passive IR sensor. Usually, in the infrared spectrum, all the objects radiate some form of thermal radiations. These types of radiations are invisible to our eyes, that can be detected by an infrared sensor. The emitter is simply an IR LED (Light Emitting Diode) and the detector is simply an IR photodiode which is sensitive to IR light of the same wavelength as that emitted by the IR LED.
When IR light falls on the photodiode, The resistances and these output voltages, change in proportion to the magnitude of the IR light received.

# references
[1] https://www.google.co.in/

[2] https://howtomechatronics.com/tutorials/arduino/rfid-works-make-arduino-based-rfid-door-lock/

[3] https://en.wikipedia.org/wiki/Radio-frequency_identification

[4] https://en.wikipedia.org/wiki/Arduino

[5] https://opensource.com/resources/what-arduino

[6] https://www.arduino.cc
