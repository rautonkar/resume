# Project synopsis at Renesas Electronics America, Inc. #

***Ported USB Driver for GR-Sakura***

*    Ported a USB Host Driver to provide operation of HID Devices, Game Controllers, USB-Serial Converters, etc.

***Test Harness for SPI Master***

*    Created a SPI Slave device emulating a wireless modem transferring firmware image for updating the SPI master device.

***Implementation a FIT Compatible driver for Capacitive Touch Sensing Unit***

*    Implemented a highly flexible, modular, well documented and tested, peripheral driver for operating the CTSU and performing Touch Detection. The same driver is usable across multiple microcontroller architectures. 
*    Driver was used in multiple capacitive touch based applications.
*    Driver received UL Certification.

***Simplified SCRAM-SHA-1 Implementation on Synergy S7G2 Microcontroller***

*    Wrote an application note and example which demonstrated password based mutual authentication without the need to exchange the password in the clear.

***Design of multiple Bluetooth Low Energy Profiles on RL78/G1D 16-bit MCU***

*    Gained thorough understanding of Renesas Wireless Kernel Extension and RBLE stack operation in Embedded and Modem configurations.
*    Designed and tested multiple profiles to transfer data using the RBLE stack for various Healthcare Applications.

***Developed firmware for Personal Medication Adherence Solution***

*    Operate the Pill popping interface using conductive and optical sensing techniques on blister packs.
*    Perform Sensor data collection, temperature, humidity, and battery life.
*    Perform Near Field Communication to load Unique Database Identifier.
*    Bluetooth Low Energy interface to relay information to Android and iOS devices.
*    Store and reload information from programmable non-volatile memory.
*    Drive Segmented LCD for HMI.

***Developed a Test Harness demonstrating crypto capabilities of Synergy Microcontrollers***

*    Introduced a mechanism to test the interface layer between ExpressLogic NetX Secure and the Secure Cryptography Engine on the S5D9.
*    Mechanism served to input multiple test vectors and provide computed output back to the test PC.

***Firmware for Multiple Healthcare Projects***

*    Reviewed firmware for In-Transit Medication Management.
*    Reviewed firmware for Galvanic Skin Response and Body Composition Meter.
*    Implemented Continua Compliant PulseOximeter demonstrating interoperability of medical data.

***Managed successful completion of projects contracted to third-party companies***

*    Continua Compliant Healthcare Meters Kit demonstrating interoperability of medical devices.
*    Personal Medication Adherence Mobile Application development.
*    Pilot Program for Certification of Renesas Synergy Software Package to UL 2900 standards.

# Project synopsis at BNS Solutions #
***M16C62P to M16C65 firmware port***
*    Ported the SCK library by [FAST.](www.kitchenbrains.com) and firmware for multiple commercial kitchen products and equipments.

***FreeScale MC68H705 to M16C65 firmware port***

*    Ported firmware for an old product which was redesigned due to end-of-life on the old microcontroller.

***Branson Digital Extension Cable***

*    Wrote firmware for a Renesas RX62N 32-bit MCU for reproducing input signals from one unit on the output the other. Each board would transfer information using TCP/IP, CAN, or UART.

***EInk Segmented Display QSK***

*    Wrote firmware for demonstrating and driving EInk Segmented display technology using the RL78 16-bit MCU.

***Wireless Monitoring System***

*    Wrote firmware for a pair of R8C/3MQ 16-bit microcontrollers communicating to each other using 802.15.4 compliant RF communication. System was a low power system capable of achieving a battery life over six weeks for monitoring patient activity on a bed or chair.

***Fume Hood Controller-Display Panel***

*    Designed hardware and firmware for a display panel using the RX200 32-bit microcontroller, external SRAM, and a 2.8 inch TFTLCD screen. This platform became the user interface for manipulating the configuration of a Fume Hood Controller. Interface was managed by using only a Run-to-end Round Robin Scheduler and the EasyGUI library. The display panel firmware was upgradable from an SDCard.
*    Finished final firmware for the Fume Hood Controller which used a Cypress PSOC5 device as the main MCU. 

***Display panel with Resistive Touch Screen***

*    The designed display panel hardware was modified to incorporate a resistive touch screen and became the front end interface for another product.

***Three Phase BLDC motor control with Sensors***

*    Implemented firmware for Hall Sensor based three phase brushless DC motor control using a Zilog Z16FMC MCU. This hardware computes and controls the airflow in a powered air purification system using measurements from a variety of on-board sensors like a differential pressure sensor, NTC, altitude sensor and a humidity sensor.

***MicroCOS-III based Medical Bracket board***

*    Modified an existing demo application using the microC OS-III RTOS on a Renesas RX111 32-bit MCU. Wrote device drivers for UART, and I2C to interface to other peripherals on-board the System

***Non-breakable bootloader for the RX63N***

*    Created a bootloader for a performance charger using the Renesas E2 Flash Technology in a RX63N 32-bit microcontroller. The bootloader was designed such that the device would never be rendered useless if power was lost even during upgrading the firmware on the device.
