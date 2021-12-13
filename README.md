# STM32H7_Development board

In order to be familiar with STM32h750 chip and TouchGFX, I diy a development board.With some peripherals,we can use the board for helping you.
The board can Provide:

+ provide some peripheral's datesheet.
  
+ provide board's PCB and sch-libraries.

+ provide board's project-demo(STM32,TouchGFX,FreeRTOS).

## MCU Specification

+ STM32H750XB Cortex-M7

+ 128Kb Flash,1Mb RAM

+ 480MHz Clock Frq

+ BGA 240

## Peripherals

STM32 Peripherals pins and Exposed pins.

+ Peripherals pins already bind with the hardware of the board.

+ Exposed pins for the future develpoment.

### SWD

SWD interface

### ADC

### DAC

### FMC

+ SDRAM:W9825G6Kh-winbond

  + 256Mb

  + A0 - A12

  + DQ0 - DQ15

### LCD

+ RGB interface

+ LCD/IPS:40PIN  Capacitive touch
  
  + 7 inch 1000x640

  + 5 inch 800x480

+ FPC: index-0.5mm
  + PCB need to hollow out.

### QSPI

+ Nor Flash:W25Q256FVEIG
  + 256Mb
  + QSPI  

### SPI

### I2C

+ Touch chip:GT911

  + 排线出线

### SDMMC(microSD)

+ 自弹tf卡座

### UART/USART

+ UART1

+ UART3

+ UART5

### USB

+ **usb type-c** include usb-host 2.0 and supply power.

### Camera

+ digital camera interface.

### Key

+ 4 Keys

+ 1 RESET Key

+ 1 Power Key(On/off)

### LED

+ 1 Power LED

+ 1 RESET LED

+ 1 RGB LED

### Exposed pins

## Hardware

Hardware Version 1.0

### DateSheet

the information of chip used on the board

### PCB

PCB software tools used:

1. Altuim designer

2. 嘉立创打板软件

## Software

Software Version 1.0

### Firmware

### STM32

the software tools used:

1. STM32cubeMX(6.40)

2. STM32cubeIDE(1.80)/Keil5(5.32)

3. TouchGFX(1.81)

## Update details

### V1.0(2021-12-12)

Hardware VR:1.0
Provide board-hardware details
Software VR:1.0
Provide board-software details
