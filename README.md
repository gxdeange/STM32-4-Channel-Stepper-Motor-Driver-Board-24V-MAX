# STM32 4-Channel Stepper Motor Driver Board @24V MAX

STM32F401RCT6 based Stepper Motor Driver capable of running at 24V MAX.

This board is designed for experimental or low current robotics with a max current drive of ~800mA.

Features include:

* Reverse Polarity Protection (with LED indicator)
* Adjustable current setting via VREF potentiometer)
* 12 X GPIO solder pads (can use standard 2.54mm Dupont Header pins)
* 4 of the GPIO solder pads with R/C input filtering (PC1, PC0, PA1, PB9)
* USB Mini Connector
* Small Form Factor (Approx 28mm X 64mm)

  <img width="311" alt="STM32 4 Channel Stepper Motor Driver Board" src="https://github.com/gxdeange/STM32-4-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/7ffd2c80-ab13-4f3a-bdd3-320f27efda8c">

# Motor Driver / MCU Pin Mappings

Motor 1: 
* STEP1 - PA11
* DIR1 - PA10
* EN1 - PA9
  
Motor2:
* STEP2 - PA8
* DIR2 - PC9
* EN2 - PC8
  
Motor 3:
* STEP3 - PC7
* DIR3 - PC6
* EN3 - PB15
  
Motor 4:
* STEP4 - PB14
* DIR4 - PB13
* EN4 - PB12

<img width="953" alt="STM32 4 Channel Pin Mappings" src="https://github.com/gxdeange/STM32-4-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/c845d6c5-13ff-4c0a-a196-fcc7b8943a82">
