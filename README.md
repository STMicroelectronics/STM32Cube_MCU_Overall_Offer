# STM32Cube_MCU_Overall_Offer

## Overview

**STM32Cube** is an STMicroelectronics original initiative to ease the developers life by reducing efforts, time and cost.

**STM32Cube** covers the overall STM32 products portfolio (MCU and MPU). It includes a comprehensive embedded software platform, delivered for each STM32 series.
   * The CMSIS modules (core and device) corresponding to the ARM(tm) core implemented in this STM32 product
   * The STM32 HAL-LL drivers : an abstraction drivers layer, the API ensuring maximized portability across the STM32 portfolio
   * The BSP Drivers of each evaluation or demonstration board provided by this STM32 series
   * A consistent set of middlewares components such as RTOS, USB, FatFS, Graphics, TCP/IP, BLE, STM32_TouchSensing_Library ...
   * A full set of software projects (basic examples, applications or demonstrations) for each board provided by this STM32 series

GitHub is a new publication model for the STM32Cube MCU embedded software. Two models of publication are proposed:
   * The **MCU Package** : monolithic STM32Cube software modules, per STM32 MCU series (Drivers, Middlewares, Utilities, Examples Projects) in an unique repo. The usual name of a STM32MCU Package is **STM32Cubexx**, xx corresponding to the STM32 series). Please refer to the chapter **STM32Cube MCU Packages** below.

   * The **MCU components** : parts of the MCU Packages, proposed as individual repos, allowing the user to select and get only the required software functions. Please refer to the chapter **STM32Cube MCU Components** below.

Please note that a MPU offer is also proposed for the **STM32 MPU Products**. You can refer to the repo [STM32MPU_EmbSW_Overall_Offer](https://github.com/STMicroelectronics/STM32MPU_EmbSW_Overall_Offer)


## Description

This repo is a simple Readme describing all STM32 MCU related GitHub projects, the overall offer for the STM32 MCU products.

This new publication channel of the STM32Cube embedded software components will provide new added values :
   * In complement to the MCU Package zip files today proposed on **st.com**, the capability for STM32 customers to get a configuration management based delivery (Git)
   * A more direct communication between developers, thanks to the Issues features. **Caution** : only software related questions will be taken into account. Any other subject must be submitted to the [ST Community](https://community.st.com/stm32mcu) forum
   * Thanks to the deployment of a Contributor License Agreement feature (please refer to each repo CONTRIBUTING guide), the **Pull-Request** permits also to take into account customers proposed updates and enrich the STM32Cube FW offer.


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
[STM32CubeL5](https://github.com/STMicroelectronics/STM32CubeL5) | The STM32CubeL5 FW MCU Package
[STM32CubeWB](https://github.com/STMicroelectronics/STM32CubeWB) | The STM32CubeWB FW MCU Package
.... | ....
more to come | ....


### STM32Cube MCU Components

As mentioned above, the STM32Cube Components is an alternative delivery model to the STM32 Packages. In this case, each module is delivered as individual repos, allowing the customer to select and download only the pertinent features.
   * Components available today : CMSIS - HAL/LL - Base MW (USB, FatFS, FrreRTOS, LwIP)
   * Components upcoming : Other MW - BSP - Utilities 

In each module README file you will find the cross compatibility information. When all modules will be available a set of new Manifest files (series by series) will be proposed to drive the user.

#### STM32Cube CMSIS

STM32Cube CMSIS core | Description
---------------------| -----------
[cmsis_core](https://github.com/STMicroelectronics/cmsis_core) | The STM32 CMSIS Core, issued from ARM (tm) publication. Please check the ST_README.md file.

STM32Cube CMSIS Devices | Description
------------------------| -----------
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
[cmsis_device_l5](https://github.com/STMicroelectronics/cmsis_device_l5) | The STM32L5 CMSIS Device files
[cmsis_device_wb](https://github.com/STMicroelectronics/cmsis_device_wb) | The STM32WB CMSIS Device files
.... | ....
more to come | ....


#### STM32Cube HAL Drivers

The **HAL Drivers** MCU Components propose the HAL and LL Drivers modules controlling all the HW IPs embedded in the STM32 product

* HAL Drivers:
  * A set of portable abstraction APIs offering high level services, built around standalone processes. The HAL drivers are functionalities oriented, example: for the Timer peripheral, the APIs could be split into several categories following the functions offered by the IPs (Basic timer, capture, PWM …etc.) for a communication IP: an initialisation function, eventually a configuration function and data transfer services (polling, interruption or DMA based)
  * The compatibility SHALL be guaranteed across all the STM32 families for the generic APIs, including generic macros and common structures defines. Any specific feature is given in a dedicated extension model available in the associated extension files

* LL Drivers:
  * Low Layer Drivers: a set of basic functions with direct hardware access (no standalone process), this layer can be called either by applications or by the HAL drivers.

HAL and LL Drivers are provided in the same module/repo

The dynamic usage of HAL APIs is provided thru projects examples, available in the respective STM32Cube MCU Packages **STM32Cubexx** where xx correspond to the series


STM32Cube HAL Drivers | Description
--------------------- | -----------
[stm32f0xx_hal_driver](https://github.com/STMicroelectronics/stm32f0xx_hal_driver) | The STM32F0 HAL-LL Drivers
[stm32f1xx_hal_driver](https://github.com/STMicroelectronics/stm32f1xx_hal_driver) | The STM32F1 HAL-LL Drivers
[stm32f2xx_hal_driver](https://github.com/STMicroelectronics/stm32f2xx_hal_driver) | The STM32F2 HAL-LL Drivers
[stm32f3xx_hal_driver](https://github.com/STMicroelectronics/stm32f3xx_hal_driver) | The STM32F3 HAL-LL Drivers
[stm32f4xx_hal_driver](https://github.com/STMicroelectronics/stm32f4xx_hal_driver) | The STM32F4 HAL-LL Drivers
[stm32f7xx_hal_driver](https://github.com/STMicroelectronics/stm32f7xx_hal_driver) | The STM32F7 HAL-LL Drivers
[stm32g0xx_hal_driver](https://github.com/STMicroelectronics/stm32g0xx_hal_driver) | The STM32G0 HAL-LL Drivers
[stm32g4xx_hal_driver](https://github.com/STMicroelectronics/stm32g4xx_hal_driver) | The STM32G4 HAL-LL Drivers
[stm32h7xx_hal_driver](https://github.com/STMicroelectronics/stm32h7xx_hal_driver) | The STM32H7 HAL-LL Drivers
[stm32l0xx_hal_driver](https://github.com/STMicroelectronics/stm32l0xx_hal_driver) | The STM32L0 HAL-LL Drivers
[stm32l1xx_hal_driver](https://github.com/STMicroelectronics/stm32l1xx_hal_driver) | The STM32L1 HAL-LL Drivers
[stm32l4xx_hal_driver](https://github.com/STMicroelectronics/stm32l4xx_hal_driver) | The STM32L4 HAL-LL Drivers
[stm32l5xx_hal_driver](https://github.com/STMicroelectronics/stm32l5xx_hal_driver) | The STM32L5 HAL-LL Drivers
[stm32wbxx_hal_driver](https://github.com/STMicroelectronics/stm32wbxx_hal_driver) | The STM32WB HAL-LL Drivers
.... | ....
more to come | ....

#### STM32Cube Middleware Libraries

The **Middleware Libraries** MCU Components propose the following set of stacks common to all STM32xx series very useful to design number of middleware-based user applications.

* FatFS library:
  * A set of platform- and storage device-independent services allowing user application to access storage devices and manage files.

* FreeRTOS library:
  * A set of platform-independent services implementing a real-time operating system kernel for embedded devices and providing methods for multiple threads or tasks, mutexes, semaphores and software timers.

* LwIP library:
  * lwIP (lightweight IP) is an open-source TCP/IP stack designed to reduce resource usage while still offering a full-scale TCP stack. Among other services, it also offers a network interface, buffers and a memory management section, and an operating system emulation layer.

* USB Device library:
  * A set of services allowing the configuration and the control of the USB on STM32 MCUs in device mode. It is mainly based on the "Core" and the "Class" modules including the common and most used features and APIs.

* USB Host library:
  * A set of services allowing the configuration and the control of the USB on STM32 MCUs in host mode. It is mainly based on the "Core" and the "Class" modules including the common and most used features and APIs.

The dynamic usage of Middleware Libraries is provided thru projects examples, available in the respective STM32Cube MCU Packages **STM32Cubexx** where xx correspond to the series.

STM32Cube MW Libraries | Description
---------------------- | -----------
[stm32_mw_fatfs](https://github.com/STMicroelectronics/stm32_mw_fatfs) | FatFS middleware library
[stm32_mw_freertos](https://github.com/STMicroelectronics/stm32_mw_freertos) | FreeRTOS middleware library
[stm32_mw_lwip](https://github.com/STMicroelectronics/stm32_mw_lwip) | LwIP middleware library
[stm32_mw_usb_device](https://github.com/STMicroelectronics/stm32_mw_usb_device) | USB Host middleware library
[stm32_mw_usb_host](https://github.com/STMicroelectronics/stm32_mw_usb_host) | USB Device middleware library
.... | ....
more to come | ....
