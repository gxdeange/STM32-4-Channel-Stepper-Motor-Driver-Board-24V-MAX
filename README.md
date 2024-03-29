# STM32 4-Channel Stepper Motor Driver Board @24V MAX

STM32F401RCT6 based Stepper Motor Driver capable of running at 24V MAX.

This board is designed for experimental or low current applications with a max current drive of ~800mA.

Features include:

* Reverse Polarity Protection (with LED indicator)
* Adjustable current setting via VREF potentiometer)
* 12 X GPIO solder pads (can use standard 2.54mm Dupont Header pins)
* 4 of the GPIO solder pads with R/C input filtering (PC1, PC0, PA1, PB9)
* USB Mini Connector
* MicroStep set to 1/8
* **All GPIO Inputs / Outputs are rated at 3.3V**
* Small Form Factor (Approx 28mm X 64mm)

  <img width="311" alt="STM32 4 Channel Stepper Motor Driver Board" src="https://github.com/gxdeange/STM32-4-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/7ffd2c80-ab13-4f3a-bdd3-320f27efda8c">

# STM32 4-Channel Stepper Motor Driver Board with Adjustable Micro Stepping @24V MAX

* Adjustable MicroStep settings via M0 and M1 slide switches
* Small Form Factor (Approx 30.5mm X 64mm)
* **All GPIO Inputs / Outputs are rated at 3.3V**

  <img width="324" alt="STM32f401RCT6 4 Channel Stepper Motor Driver M:Step" src="https://github.com/gxdeange/STM32-4-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/cc28e04b-da89-4f3b-bfe5-a26c47f9fa0b">

# STM32 4-Channel Stepper Motor Driver Board With Buffered, Schmitt Trigger Inputs (8 X GPIO's) and Adjustable Micro Stepping @24V Max

* 8 of the GPIO solder pads have buffered Schmitt trigger inputs (PA1, PA4, PC0, PC1, PA12, PB7, PB8, PB9)
* Inputs for above 10 GPIO's are pulled High (3.3V via 10K resistor)

  <img width="344" alt="STM32F401RCT6 4 Channel Stepper Driver Buffered MS" src="https://github.com/gxdeange/STM32-4-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/81d3984f-6f12-4dfb-a3bf-9f836200ba3f">

![image](https://github.com/gxdeange/STM32-4-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/1e2cae3d-8127-47e2-8f4b-791313abe674)

# Motor Driver / MCU Pin Mappings

![image](https://github.com/gxdeange/STM32-4-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/2026c2c4-9cc1-4692-afd2-9b9e26087b16)


  <img width="953" alt="STM32 4 Channel Pin Mappings" src="https://github.com/gxdeange/STM32-4-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/c845d6c5-13ff-4c0a-a196-fcc7b8943a82">

# PROGRAMMING NOTE

This MCU does not use an external crystal. The Internal RC Clock (HSI) must be initialised at the start of your code.
