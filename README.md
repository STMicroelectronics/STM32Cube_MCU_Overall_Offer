# STM32Cube_MCU_Overall_Offer

## Overview

**STM32Cube** is an STMicroelectronics original initiative to ease the developers life by reducing efforts, time and cost.

**STM32Cube** covers the overall STM32 products portfolio (MCU and MPU). It includes a comprehensive embedded software platform, delivered for each STM32 series.
   * The CMSIS modules (core and device) corresponding to the ARM(tm) core implemented in this STM32 product
   * The STM32 HAL-LL drivers : an abstraction drivers layer, the API ensuring maximized portability across the STM32 portfolio 
   * The BSP Drivers of each evaluation or demonstration board provided by this STM32 series 
   * A consistent set of middlewares components such as RTOS, USB, FatFS, Graphics, TCP/IP, BLE, STM32_TouchSensing_Library ...
   * A full set of software projects (basic examples, applications or demonstrations) for each board provided by this STM32 series

This is a new publication model for the STM32Cube MCU embedded software.Two models of publication are proposed  : 
   * The monolithic **MCU Package** : all STM32Cube software modules of one STM32 MCU series are present (Drivers, Middlewares, Utilities) in an unique repo, with various examples projects. The usual name of a STM32MCU Package is **STM32Cubexx**, xx corresponding to the STM32 series). Please refer to the chapter **STM32Cube MCU Packages** below.

   * From Q4'19, the **MCU components**, parts the MCU Packages, will be progressively delivered as individual repos, allowing the user to select and get only the required software functions.Please refer to the chapter **STM32Cube MCU Components** below.

Please note that a MPU offer is also proposed for the **STM32 MPU Products**. You can refer to the repo [STM32MPU_EmbSW_Overall_Offer](https://github.com/STMicroelectronics/STM32MPU_EmbSW_Overall_Offer)
  
   
## Description

This repo is a simple Readme describing all STM32 MCU related GitHub projects, the open source offer for the STM32 MCU products.

This new publication channel of the STM32Cube embedded software components will provide new added values :
   * In complement to the MCU Package zip files today proposed on **st.com**, the capability for STM32 customers to get a configuration management based delivery (Git)
   * A more direct communication between developers, thanks to the Issues features. **Caution** : only software related questions will be taken into account. Any other subject must be submitted to the [ST Community](https://st-microelectronics.jiveon.com/welcome) forum 
   * In a second phase (after the deployment of a Contributor License Agreement mechanism), the **Pull-Request** will permit to take into account customers proposed updates and enrich the STM32Cube FW offer. 


For general communication and support, you can use
   * [ST Support Center](https://my.st.com/ols#/ols/) for any defect
   * [ST Community Forum](https://community.st.com/stm32mcu) forum 

   
### STM32Cube MCU Packages   
 
STM32Cube MCU Packages | Description
---------------------- | -----------
[STM32CubeF0](https://github.com/STMicroelectronics/STM32CubeF0) | The STM32CubeF0 FW MCU Package
[STM32CubeF1](https://github.com/STMicroelectronics/STM32CubeF1) | The STM32CubeF1 FW MCU Package
[STM32CubeF2](https://github.com/STMicroelectronics/STM32CubeF2) | The STM32CubeF2 FW MCU Package
[STM32CubeF3](https://github.com/STMicroelectronics/STM32CubeF3) | The STM32CubeF3 FW MCU Package
[STM32CubeF4](https://github.com/STMicroelectronics/STM32CubeF4) | The STM32CubeF4 FW MCU Package
[STM32CubeF7](https://github.com/STMicroelectronics/STM32CubeF7) | The STM32CubeF7 FW MCU Package
[STM32CubeH7](https://github.com/STMicroelectronics/STM32CubeH7) | The STM32CubeH7 FW MCU Package
[STM32CubeG0](https://github.com/STMicroelectronics/STM32CubeG0) | The STM32CubeG0 FW MCU Package
[STM32CubeG4](https://github.com/STMicroelectronics/STM32CubeG4) | The STM32CubeG4 FW MCU Package
[STM32CubeL0](https://github.com/STMicroelectronics/STM32CubeL0) | The STM32CubeL0 FW MCU Package
[STM32CubeL1](https://github.com/STMicroelectronics/STM32CubeL1) | The STM32CubeL1 FW MCU Package
[STM32CubeL4](https://github.com/STMicroelectronics/STM32CubeL4) | The STM32CubeL4 FW MCU Package
[STM32CubeWB](https://github.com/STMicroelectronics/STM32CubeWB) | The STM32CubeWB FW MCU Package
.... | ....
more to come | ....


### STM32Cube MCU Components 

As mentioned above, the STM32Cube Components is an alternative delivery model to the STM32 Packages. In this case, each module is delivered as individual repos, allowing the customer to select and download only the pertinent features.

In December 2019, the CMSIS modules are proposed. The next update will contain the HAL-LL Drivers. Then the Middleware modules. (target Q1'20). 

In each module README file you will find the cross compatibility information. When all modules will be available a set of new Manifest files (series by series) will be proposed to drive the user.

STM32Cube CMSIS core | Description
--------------------------- | -----------
[cmsis_core](https://github.com/STMicroelectronics/cmsis_core) | The STM32 CMSIS Core, issued from ARM (tm) publication. Please check the ST_README.md file.

STM32Cube CMSIS Devices | Description
--------------------------- | -----------
[cmsis_device_f0](https://github.com/STMicroelectronics/cmsis_device_f0) | The STM32F0 CMSIS Device files
[cmsis_device_f1](https://github.com/STMicroelectronics/cmsis_device_f1) | The STM32F1 CMSIS Device files
[cmsis_device_f2](https://github.com/STMicroelectronics/cmsis_device_f2) | The STM32F2 CMSIS Device files
[cmsis_device_f3](https://github.com/STMicroelectronics/cmsis_device_f3) | The STM32F3 CMSIS Device files
[cmsis_device_f4](https://github.com/STMicroelectronics/cmsis_device_f4) | The STM32F4 CMSIS Device files
[cmsis_device_f7](https://github.com/STMicroelectronics/cmsis_device_f7) | The STM32F7 CMSIS Device files
[cmsis_device_g0](https://github.com/STMicroelectronics/cmsis_device_g0) | The STM32G0 CMSIS Device files
[cmsis_device_g4](https://github.com/STMicroelectronics/cmsis_device_g4) | The STM32G4 CMSIS Device files
[cmsis_device_h7](https://github.com/STMicroelectronics/cmsis_device_h7) | The STM32H7 CMSIS Device files
[cmsis_device_l0](https://github.com/STMicroelectronics/cmsis_device_l0) | The STM32L0 CMSIS Device files
[cmsis_device_l1](https://github.com/STMicroelectronics/cmsis_device_l1) | The STM32L1 CMSIS Device files
[cmsis_device_l4](https://github.com/STMicroelectronics/cmsis_device_l4) | The STM32L4 CMSIS Device files
[cmsis_device_wb](https://github.com/STMicroelectronics/cmsis_device_wb) | The STM32WB CMSIS Device files
.... | ....
more to come | ....





