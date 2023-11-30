# STM32Cube MCU Overall Offer

## Overview

**STM32Cube** is an STMicroelectronics original initiative to ease the developers life by reducing efforts, time and cost.

**STM32Cube** covers the overall STM32 products portfolio (MCU and MPU). It includes a comprehensive embedded software platform, delivered for each STM32 series.

* The CMSIS modules (core and device) corresponding to the ARM(tm) core implemented in this STM32 product.
* The STM32 HAL-LL drivers, an abstraction layer offering a set of APIs ensuring maximized portability across the STM32 portfolio.
* The BSP drivers of each evaluation, demonstration, or nucleo board provided for this STM32 series.
* A consistent set of middleware libraries such as RTOS, USB, FatFS, graphics, touch sensing library...
* A full set of software projects (basic examples, applications, and demonstrations) for each board provided for this STM32 series.

GitHub is a new publication model for the STM32Cube MCU embedded software. Different models of publication are proposed:

* The **MCU Package**: A unique repo per STM32 MCU series containing the different components of a STM32 MCU firmware (Drivers, Middleware, Utilities, Examples). Please refer to the [STM32Cube MCU Packages](README.md#stm32cube-mcu-packages) chapter below.
* The **MCU components**: Each component of a STM32 MCU firmware (Drivers, Middleware, Utilities) is proposed in a dedicated repo, allowing the user to select and get only the required ones. Please refer to the [STM32Cube MCU Components](README.md#stm32cube-mcu-components) chapter below.
* The **X-CUBE**: Expansion software proposing examples and applications that complement the ones of the STM32Cube firmware.
* A set of **MCU Utilities**: Various utility features proposed in dedicated repos.

Please note that a MPU offer is also proposed for the **STM32 MPU Products**. You can refer to the repo [STM32MPU_EmbSW_Overall_Offer](https://github.com/STMicroelectronics/STM32MPU_EmbSW_Overall_Offer).

## Description

This repo is a simple Readme describing all STM32 MCU related GitHub projects, the overall offer for the STM32 MCU products.

This new publication channel of the STM32Cube embedded software components will provide new added values:

* In complement to the MCU Package zip files today proposed on **st.com**, the capability for STM32 customers to get a configuration management based delivery (Git)
* A more direct communication between developers, thanks to the Issues features. **Caution**: only software related questions will be taken into account. Any other subject must be submitted to the [ST Community](https://community.st.com/stm32mcu) forum
* Thanks to the deployment of a Contributor License Agreement feature (please refer to each repo CONTRIBUTING guide), the **Pull-Request** permits also to take into account customers proposed updates and enrich the STM32Cube FW offer.

For general communication and support, you can use

* [ST Support Center](https://my.st.com/ols#/ols/) for any defect
* [ST Community Forum](https://community.st.com/stm32mcu) forum

## Content

* [STM32Cube MCU Packages](README.md#stm32cube-mcu-packages)
* [STM32Cube X-CUBE](README.md#x-cube-expansion-softwares)
* [STM32Cube Function Packs](README.md#stm32cube-function-packs)
* [STM32Cube CMSIS](README.md#stm32cube-cmsis)
* [STM32Cube HAL Drivers](README.md#stm32cube-hal-drivers)
* [STM32Cube BSP Drivers](README.md#stm32cube-bsp-drivers)
* [STM32Cube MW Libraries and Applications](README.md#stm32cube-middleware-libraries-and-applications)
* [STM32Cube Utilities and miscellaneous](README.md#stm32cube-utilities-and-miscellaneous-repos)

## STM32Cube MCU Packages

STM32Cube MCU Packages | Description
---------------------- | -----------
[STM32CubeC0](https://github.com/STMicroelectronics/STM32CubeC0)   | The STM32CubeC0  FW MCU Package
[STM32CubeF0](https://github.com/STMicroelectronics/STM32CubeF0)   | The STM32CubeF0  FW MCU Package
[STM32CubeF1](https://github.com/STMicroelectronics/STM32CubeF1)   | The STM32CubeF1  FW MCU Package
[STM32CubeF2](https://github.com/STMicroelectronics/STM32CubeF2)   | The STM32CubeF2  FW MCU Package
[STM32CubeF3](https://github.com/STMicroelectronics/STM32CubeF3)   | The STM32CubeF3  FW MCU Package
[STM32CubeF4](https://github.com/STMicroelectronics/STM32CubeF4)   | The STM32CubeF4  FW MCU Package
[STM32CubeF7](https://github.com/STMicroelectronics/STM32CubeF7)   | The STM32CubeF7  FW MCU Package
[STM32CubeH5](https://github.com/STMicroelectronics/STM32CubeH5)   | The STM32CubeH5  FW MCU Package
[STM32CubeH7](https://github.com/STMicroelectronics/STM32CubeH7)   | The STM32CubeH7  FW MCU Package
[STM32CubeG0](https://github.com/STMicroelectronics/STM32CubeG0)   | The STM32CubeG0  FW MCU Package
[STM32CubeG4](https://github.com/STMicroelectronics/STM32CubeG4)   | The STM32CubeG4  FW MCU Package
[STM32CubeL0](https://github.com/STMicroelectronics/STM32CubeL0)   | The STM32CubeL0  FW MCU Package
[STM32CubeL1](https://github.com/STMicroelectronics/STM32CubeL1)   | The STM32CubeL1  FW MCU Package
[STM32CubeL4](https://github.com/STMicroelectronics/STM32CubeL4)   | The STM32CubeL4  FW MCU Package
[STM32CubeL5](https://github.com/STMicroelectronics/STM32CubeL5)   | The STM32CubeL5  FW MCU Package
[STM32CubeU5](https://github.com/STMicroelectronics/STM32CubeU5)   | The STM32CubeU5  FW MCU Package
[STM32CubeWB](https://github.com/STMicroelectronics/STM32CubeWB)   | The STM32CubeWB  FW MCU Package
[STM32CubeWBA](https://github.com/STMicroelectronics/STM32CubeWBA) | The STM32CubeWBA FW MCU Package
[STM32CubeWL](https://github.com/STMicroelectronics/STM32CubeWL)   | The STM32CubeWL  FW MCU Package

## X-CUBE Expansion softwares

The STM32Cube expansion software contains embedded software components that complement the functionalities of the STM32Cube and/or enable the usage of a multitude of ST devices in domains such as of sensing, power management, connectivity or audio, together with the most appropriate STM32 MCUs.

STM32Cube Azure RTOS X-CUBE | Description
--------------------------- | -----------
[x-cube-azrtos-f4](https://github.com/STMicroelectronics/x-cube-azrtos-f4) | Azure RTOS Expansion Package for STM32Cube, for STM32F4 series.
[x-cube-azrtos-f7](https://github.com/STMicroelectronics/x-cube-azrtos-f7) | Azure RTOS Expansion Package for STM32Cube, for STM32F7 series.
[x-cube-azrtos-g0](https://github.com/STMicroelectronics/x-cube-azrtos-g0) | Azure RTOS Expansion Package for STM32Cube, for STM32G0 series.
[x-cube-azrtos-g4](https://github.com/STMicroelectronics/x-cube-azrtos-g4) | Azure RTOS Expansion Package for STM32Cube, for STM32G4 series.
[x-cube-azrtos-h7](https://github.com/STMicroelectronics/x-cube-azrtos-h7) | Azure RTOS Expansion Package for STM32Cube, for STM32H7 series.
[x-cube-azrtos-l4](https://github.com/STMicroelectronics/x-cube-azrtos-l4) | Azure RTOS Expansion Package for STM32Cube, for STM32L4 series.
[x-cube-azrtos-l5](https://github.com/STMicroelectronics/x-cube-azrtos-l5) | Azure RTOS Expansion Package for STM32Cube, for STM32L5 series.
[x-cube-azrtos-wb](https://github.com/STMicroelectronics/x-cube-azrtos-wb) | Azure RTOS Expansion Package for STM32Cube, for STM32WB series.
[x-cube-azrtos-wl](https://github.com/STMicroelectronics/x-cube-azrtos-wl) | Azure RTOS Expansion Package for STM32Cube, for STM32WL series.

STM32Cube Connectivity X-CUBE | Description
----------------------------- | -----------
[x-cube-ble1](https://github.com/STMicroelectronics/x-cube-ble1)           | BlueNRG-M0 Bluetooth Low Energy Expansion Package for STM32Cube.
[x-cube-ble2](https://github.com/STMicroelectronics/X-CUBE-BLE2)           | BlueNRG-2 Bluetooth Low Energy Expansion Package for STM32Cube.
[x-cube-blemgr](https://github.com/STMicroelectronics/x-cube-blemgr)       | Expansion Package to set and configure bluetooth connectivity from board to mobile application such as ST BLE Sensor.
[x-cube-nfc4](https://github.com/STMicroelectronics/X-CUBE-NFC4)           | Dynamic NFC/RFID tag IC (ST25DV04K device) Expansion Package for STM32Cube.
[x-cube-nfc7](https://github.com/STMicroelectronics/x-cube-nfc7)           | Dynamic NFC/RFID tag IC (ST25DV64KC device) Expansion Package for STM32Cube.
[x-cube-sfxs2lp1](https://github.com/STMicroelectronics/x-cube-sfxs2lp1)   | Embedded software S2-LP Sigfox library and GUI PC application to transmit messages to the Sigfox network.
[x-cube-subg2](https://github.com/STMicroelectronics/x-cube-subg2)         | Sub 1 GHz RF communication for S2-LP Expansion Package for STM32Cube.

STM32Cube FreeRTOS X-CUBE | Description
--------------------------- | -----------
[x-cube-freertos](https://github.com/STMicroelectronics/x-cube-freertos) | FreeRTOS Expansion Package for STM32H5 and STM32U5.

STM32Cube IoT X-CUBE | Description
-------------------- | -----------
[x-cube-aws](https://github.com/STMicroelectronics/x-cube-aws)                           | AWS IoT Expansion Package for STM32Cube.
[x-cube-azure-telematics](https://github.com/STMicroelectronics/x-cube-azure-telematics) | Azure IoT Expansion Package for STM32Cube.
[x-cube-iota1](https://github.com/STMicroelectronics/X-CUBE-IOTA1)                       | IOTA Distributed Ledger Technology Expansion Package for STM32Cube.

STM32Cube MEMS and Sensors X-CUBE | Description
--------------------------------- | -----------
[x-cube-ispu](https://github.com/STMicroelectronics/x-cube-ispu)           | Provides examples and drivers for STM32 to recognize sensors and collect temperature, humidity, pressure, motion, and ISPU (Intelligent Sensor Processing Unit) data.
[x-cube-mems1](https://github.com/STMicroelectronics/x-cube-mems1)         | X-CUBE-MEMS1 Expansion Package for STM32Cube. (X-NUCLEO-IKS01A2, X-NUCLEO-IKS01A3 and X-NUCLEO-IKS02A1).
[x-cube-memsmic1](https://github.com/STMicroelectronics/x-cube-memsmic1)   | Provides examples for STM32 using ST analog and digital MEMS microphones, and ultrasound condition monitoring (UltrasoundFFT).
[x-cube-soundter1](https://github.com/STMicroelectronics/x-cube-soundter1) | Provides drivers and middleware for STM32 to interface with the STA350BW Sound Terminal component mounted on X-NUCLEO-CCA01M1 expansion board.

STM32Cube USB-PD X-CUBE | Description
----------------------- | -----------
[x-cube-tcpp](https://github.com/STMicroelectronics/x-cube-tcpp)           | USB-IF certified Expansion Package for the integration of TCPPs protection circuits (OV/OC).
[x-cube-usb-pd](https://github.com/STMicroelectronics/x-cube-usb-pd)       | USB-IF certified Expansion Package as USB Type-C port manager (TCPM).

STM32Cube Miscellaneous X-CUBE | Description
------------------------------ | -----------
[x-cube-eeprma1](https://github.com/STMicroelectronics/X-CUBE-EEPRMA1)     | M24XX I2C and M95XX SPI EEPROMs Expansion Package for STM32Cube.
[x-cube-gnss1](https://github.com/STMicroelectronics/x-cube-gnss1)         | Teseo-LIV3F GNSS Expansion Package for STM32Cube.

## STM32Cube Function Packs

STM32 Function Packs (FP) are a combination of low-level drivers, middleware libraries and sample applications assembled into a single software package. You can get the entire list of available Function Packs on st.com [here](https://www.st.com/en/ecosystems/stm32-ode-function-packs.html).

The below list represents the Function Packs available on github.com

STM32Cube Function Packs | Description
------------------------ | -----------
[fp-atr-ble1](https://github.com/STMicroelectronics/fp-atr-ble1)           | STM32Cube function pack for asset tracking using BLE&NFC connectivity for SensorTile.box PRO discovery box.
[fp-atr-sigfox1](https://github.com/STMicroelectronics/fp-atr-sigfox1)     | STM32Cube function pack for reading data from GNSS and environmental sensors and sending this information via Sigfox.
[fp-aud-aec1](https://github.com/STMicroelectronics/fp-aud-aec1)           | STM32Cube function pack for Acoustic Echo Cancellation implementing a USB smart speaker use case with microphone.
[fp-aud-smartmic1](https://github.com/STMicroelectronics/fp-aud-smartmic1) | STM32Cube function pack for acquiring audio signals from 4 digital MEMS microphones, processing them, and streaming them to both a USB host and a loudspeaker.
[fp-sns-allmems1](https://github.com/STMicroelectronics/fp-sns-allmems1)   | STM32Cube function pack for IoT node with BLE connectivity to view environmental and intertial sensors data, plus some advanced functionalities (e.g., voice communication over BLE, sound source localization).
[fp-sns-datalog1](https://github.com/STMicroelectronics/fp-sns-datalog1)   | STM32Cube function pack for IoT node with BLE connectivity to save data from any combination of sensors and microphones configured up to the maximum sampling rate.
[fp-sns-datalog2](https://github.com/STMicroelectronics/fp-sns-datalog2)   | STM32Cube function pack for IoT node with BLE connectivity to save data from any combination of sensors and microphones configured up to the maximum sampling rate (evolution of the [fp-sns-datalog1](https://github.com/STMicroelectronics/fp-sns-datalog1) pack).
[fp-sns-flight1](https://github.com/STMicroelectronics/fp-sns-flight1)     | STM32Cube function pack for IoT node with BLE connectivity to view time-of-flight sensors data in real-time.
[fp-sns-motenv1](https://github.com/STMicroelectronics/FP-SNS-MOTENV1)     | STM32Cube function pack for IoT node with BLE connectivity to view environmental and intertial sensors data for F4, L0, and L4 based on the BlueNRG transceiver.
[fp-sns-motenvwb1](https://github.com/STMicroelectronics/fp-sns-motenvwb1) | STM32Cube function pack for IoT node with BLE connectivity to view environmental and intertial sensors data for WB.
[fp-sns-smartag2](https://github.com/STMicroelectronics/fp-sns-smartag2)   | STM32Cube function pack for IoT node to read the ambient light, motion, and environmental sensor data by means of a NFC-enabled reader.
[fp-sns-stbox1](https://github.com/STMicroelectronics/fp-sns-stbox1)       | STM32Cube function pack for the Pro Mode of wireless multi sensor development kits.

## STM32Cube MCU Components

As mentioned above, the STM32Cube Components is an alternative delivery model to the STM32 Packages. In this case, each module is delivered as individual repos, allowing the customer to select and download only the pertinent features.

* Components available today: CMSIS - HAL/LL - BSP - Base MW (USB, FatFS, FreeRTOS, LwIP)
* Components upcoming: Other MW - Utilities

In each module README file you will find the cross compatibility information. When all modules will be available a set of new Manifest files (series by series) will be proposed to drive the user.

### STM32Cube CMSIS

STM32Cube CMSIS core | Description
---------------------| -----------
[cmsis_core](https://github.com/STMicroelectronics/cmsis_core) | The STM32 CMSIS Core, issued from ARM (tm) publication. Please check the ST_README.md file.

STM32Cube CMSIS Devices | Description
------------------------| -----------
[cmsis_device_c0](https://github.com/STMicroelectronics/cmsis_device_c0) | The STM32C0 CMSIS Device files
[cmsis_device_f0](https://github.com/STMicroelectronics/cmsis_device_f0) | The STM32F0 CMSIS Device files
[cmsis_device_f1](https://github.com/STMicroelectronics/cmsis_device_f1) | The STM32F1 CMSIS Device files
[cmsis_device_f2](https://github.com/STMicroelectronics/cmsis_device_f2) | The STM32F2 CMSIS Device files
[cmsis_device_f3](https://github.com/STMicroelectronics/cmsis_device_f3) | The STM32F3 CMSIS Device files
[cmsis_device_f4](https://github.com/STMicroelectronics/cmsis_device_f4) | The STM32F4 CMSIS Device files
[cmsis_device_f7](https://github.com/STMicroelectronics/cmsis_device_f7) | The STM32F7 CMSIS Device files
[cmsis_device_g0](https://github.com/STMicroelectronics/cmsis_device_g0) | The STM32G0 CMSIS Device files
[cmsis_device_g4](https://github.com/STMicroelectronics/cmsis_device_g4) | The STM32G4 CMSIS Device files
[cmsis_device_h5](https://github.com/STMicroelectronics/cmsis_device_h5) | The STM32H5 CMSIS Device files
[cmsis_device_h7](https://github.com/STMicroelectronics/cmsis_device_h7) | The STM32H7 CMSIS Device files
[cmsis_device_l0](https://github.com/STMicroelectronics/cmsis_device_l0) | The STM32L0 CMSIS Device files
[cmsis_device_l1](https://github.com/STMicroelectronics/cmsis_device_l1) | The STM32L1 CMSIS Device files
[cmsis_device_l4](https://github.com/STMicroelectronics/cmsis_device_l4) | The STM32L4 CMSIS Device files
[cmsis_device_l5](https://github.com/STMicroelectronics/cmsis_device_l5) | The STM32L5 CMSIS Device files
[cmsis_device_u5](https://github.com/STMicroelectronics/cmsis_device_u5) | The STM32U5 CMSIS Device files
[cmsis_device_wb](https://github.com/STMicroelectronics/cmsis_device_wb) | The STM32WB CMSIS Device files
[cmsis_device_wba](https://github.com/STMicroelectronics/cmsis_device_wba) | The STM32WBA CMSIS Device files
[cmsis_device_wl](https://github.com/STMicroelectronics/cmsis_device_wl) | The STM32WL CMSIS Device files

### STM32Cube HAL Drivers

The **HAL Drivers** MCU Components propose the HAL and LL Drivers modules controlling all the HW IPs embedded in the STM32 products.

* HAL Drivers:
  * A set of portable abstraction APIs offering high level services, built around standalone processes. The HAL drivers are functionalities oriented, example: for the Timer peripheral, the APIs could be split into several categories following the functions offered by the IPs (Basic timer, capture, PWM...) for a communication IP: an initialisation function, eventually a configuration function and data transfer services (polling, interruption or DMA based)
  * The compatibility SHALL be guaranteed across all the STM32 families for the generic APIs, including generic macros and common structures defines. Any specific feature is given in a dedicated extension model available in the associated extension files

* LL Drivers:
  * Low Layer Drivers: a set of basic functions with direct hardware access (no standalone process), this layer can be called either by applications or by the HAL drivers.

HAL and LL Drivers are provided in the same module/repo

The dynamic usage of HAL APIs is provided thru projects examples, available in the respective STM32Cube MCU Packages **STM32Cubexx** where xx correspond to the series

STM32Cube HAL Drivers | Description
--------------------- | -----------
[stm32c0xx_hal_driver](https://github.com/STMicroelectronics/stm32c0xx_hal_driver) | The STM32C0 HAL-LL Drivers
[stm32f0xx_hal_driver](https://github.com/STMicroelectronics/stm32f0xx_hal_driver) | The STM32F0 HAL-LL Drivers
[stm32f1xx_hal_driver](https://github.com/STMicroelectronics/stm32f1xx_hal_driver) | The STM32F1 HAL-LL Drivers
[stm32f2xx_hal_driver](https://github.com/STMicroelectronics/stm32f2xx_hal_driver) | The STM32F2 HAL-LL Drivers
[stm32f3xx_hal_driver](https://github.com/STMicroelectronics/stm32f3xx_hal_driver) | The STM32F3 HAL-LL Drivers
[stm32f4xx_hal_driver](https://github.com/STMicroelectronics/stm32f4xx_hal_driver) | The STM32F4 HAL-LL Drivers
[stm32f7xx_hal_driver](https://github.com/STMicroelectronics/stm32f7xx_hal_driver) | The STM32F7 HAL-LL Drivers
[stm32g0xx_hal_driver](https://github.com/STMicroelectronics/stm32g0xx_hal_driver) | The STM32G0 HAL-LL Drivers
[stm32g4xx_hal_driver](https://github.com/STMicroelectronics/stm32g4xx_hal_driver) | The STM32G4 HAL-LL Drivers
[stm32h5xx_hal_driver](https://github.com/STMicroelectronics/stm32h5xx_hal_driver) | The STM32H5 HAL-LL Drivers
[stm32h7xx_hal_driver](https://github.com/STMicroelectronics/stm32h7xx_hal_driver) | The STM32H7 HAL-LL Drivers
[stm32l0xx_hal_driver](https://github.com/STMicroelectronics/stm32l0xx_hal_driver) | The STM32L0 HAL-LL Drivers
[stm32l1xx_hal_driver](https://github.com/STMicroelectronics/stm32l1xx_hal_driver) | The STM32L1 HAL-LL Drivers
[stm32l4xx_hal_driver](https://github.com/STMicroelectronics/stm32l4xx_hal_driver) | The STM32L4 HAL-LL Drivers
[stm32l5xx_hal_driver](https://github.com/STMicroelectronics/stm32l5xx_hal_driver) | The STM32L5 HAL-LL Drivers
[stm32u5xx_hal_driver](https://github.com/STMicroelectronics/stm32u5xx_hal_driver) | The STM32U5 HAL-LL Drivers
[stm32wbxx_hal_driver](https://github.com/STMicroelectronics/stm32wbxx_hal_driver) | The STM32WB HAL-LL Drivers
[stm32wbaxx_hal_driver](https://github.com/STMicroelectronics/stm32wbaxx_hal_driver) | The STM32WBA HAL-LL Drivers
[stm32wlxx_hal_driver](https://github.com/STMicroelectronics/stm32wlxx_hal_driver) | The STM32WL HAL-LL Drivers

### STM32Cube BSP Drivers

The **BSP Drivers** MCU Components propose the BSP Drivers modules, which are constituted from the:

* [STM32Cube BSP Boards Drivers](README.md#stm32cube-bsp-boards-drivers), **based on the HAL drivers**, and providing a set of high level APIs allowing a quick access to the boards services (**e.g.**, audio, graphics, access to external memories).
* [STM32Cube BSP Components Drivers](README.md#stm32cube-bsp-components-drivers) providing a set of high level APIs allowing a quick access to the (**e.g.**, audio codecs, LCD drivers, SD cards, MEMS). The **link** between these external components and the HAL drivers (**e.g.**, a SD card and the `OSPI`/`QSPI` HAL driver) is done within the **BSP Boards** drivers.

------

**NOTE:** A number of BSP **components** drivers (particularly of MEMS) come in **two forms**, each addressing a different purpose. For each one of such BSP components drivers, **two repositories** are available as explained below:

* **PID:** Platform-Independent Drivers. Recognizable to their repositories' names *\<bspcomp\>* (**e.g.**, [hts221](https://github.com/STMicroelectronics/hts221)). Are **low-level** drivers allowing direct access to components' registers. These drivers are independent of any software platform, as the acronym PID suggests. The complete list can be found [here](https://github.com/STMicroelectronics/STMems_Standard_C_drivers).

* **STM32:** STM32Cube-compatible drivers. Recognizable to their repositories' names *stm32-\<bspcomp\>* (**e.g.**, [stm32-hts221](https://github.com/STMicroelectronics/stm32-hts221)). Are **hardware-abstracted** drivers, specially designed to be compatible with the STM32Cube software offer, as the `stm32-` prefix suggests. The complete list is provided [below](README.md#stm32cube-bsp-components-drivers) (refer particularly to tables `MEMS` and `Temperature Sensor`).

------

### STM32Cube BSP Boards Drivers

STM32CubeC0 BSP Boards Drivers | Description
-------------------------------|-------------
[nucleo-c031c6-bsp](https://github.com/STMicroelectronics/nucleo-c031c6-bsp)       | NUCLEO-C031C6 BSP Driver
[stm32c0116-dk-bsp](https://github.com/STMicroelectronics/stm32c0116-dk-bsp)       | STM32C0116-DK BSP Driver
[stm32c0316-dk-bsp](https://github.com/STMicroelectronics/stm32c0316-dk-bsp)       | STM32C0316-DK BSP Driver

STM32CubeF0 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32f0xx-nucleo-32-bsp](https://github.com/STMicroelectronics/stm32f0xx-nucleo-32-bsp) | F0 nucleo 32 BSP Driver
[stm32f0xx-nucleo-bsp](https://github.com/STMicroelectronics/stm32f0xx-nucleo-bsp)       | F0 nucleo BSP Driver
[stm32091c-eval-bsp](https://github.com/STMicroelectronics/stm32091c-eval-bsp)           | STM32091C_EVAL BSP Driver
[stm32072b-eval-bsp](https://github.com/STMicroelectronics/stm32072b-eval-bsp)           | STM32072B_EVAL BSP Driver
[32f072bdiscovery-bsp](https://github.com/STMicroelectronics/32f072bdiscovery-bsp)       | 32F072BDISCOVERY BSP Driver
[32f0308discovery-bsp](https://github.com/STMicroelectronics/32f0308discovery-bsp)       | 32F0308DISCOVERY BSP Driver

STM32CubeF1 BSP Boards Drivers | Description
-------------------------------|-------------
[stm3210c-eval-bsp](https://github.com/STMicroelectronics/stm3210c-eval-bsp)       | STM3210C_EVAL BSP Driver
[stm3210e-eval-bsp](https://github.com/STMicroelectronics/stm3210e-eval-bsp)       | STM3210E_EVAL BSP Driver
[stm32f1xx-nucleo-bsp](https://github.com/STMicroelectronics/stm32f1xx-nucleo-bsp) | F1 nucleo BSP Driver
[stm32vldiscovery-bsp](https://github.com/STMicroelectronics/stm32vldiscovery-bsp) | STM32VLDISCOVERY BSP Driver

STM32CubeF2 BSP Boards Drivers | Description
-------------------------------|-------------
[stm322xg-eval-bsp](https://github.com/STMicroelectronics/stm322xg-eval-bsp)               | STM322xG_EVAL BSP Driver
[stm32f2xx-nucleo-144-bsp](https://github.com/STMicroelectronics/stm32f2xx-nucleo-144-bsp) | F2 nucleo BSP Driver

STM32CubeF3 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32303c-eval-bsp](https://github.com/STMicroelectronics/stm32303c-eval-bsp)             | STM32303C_EVAL BSP Driver
[stm32303e-eval-bsp](https://github.com/STMicroelectronics/stm32303e-eval-bsp)             | STM32303E_EVAL BSP Driver
[stm32373c-eval-bsp](https://github.com/STMicroelectronics/stm32373c-eval-bsp)             | STM32373C_EVAL BSP Driver
[stm32f3discovery-bsp](https://github.com/STMicroelectronics/stm32f3discovery-bsp)         | STM32F3-Discovery BSP Driver
[stm32f3xx-nucleo-bsp](https://github.com/STMicroelectronics/stm32f3xx-nucleo-bsp)         | F3 nucleo BSP Driver
[stm32f3xx-nucleo-144-bsp](https://github.com/STMicroelectronics/stm32f3xx-nucleo-144-bsp) | F3 nucleo 144 BSP Driver
[stm32f3xx-nucleo-32-bsp](https://github.com/STMicroelectronics/stm32f3xx-nucleo-32-bsp)   | F3 nucleo 32 BSP Driver
[32f3348discovery-bsp](https://github.com/STMicroelectronics/32f3348discovery-bsp)         | 32F3348DISCOVERY BSP Driver

STM32CubeF4 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32f4xx-nucleo-144-bsp](https://github.com/STMicroelectronics/stm32f4xx-nucleo-144-bsp) | F4 nucleo 144 BSP Driver
[stm32f4xx-nucleo-bsp](https://github.com/STMicroelectronics/stm32f4xx-nucleo-bsp)         | F4 nucleo BSP Driver
[stm324xg-eval-bsp](https://github.com/STMicroelectronics/stm324xg-eval-bsp)               | STM324xG-EVAL BSP Driver
[stm32469i-eval-bsp](https://github.com/STMicroelectronics/stm32469i-eval-bsp)             | STM32469I_EVAL BSP Driver
[32f469idiscovery-bsp](https://github.com/STMicroelectronics/32f469idiscovery-bsp)         | 32F469IDISCOVERY BSP Driver
[32f429idiscovery-bsp](https://github.com/STMicroelectronics/32f429idiscovery-bsp)         | 32F429IDISCOVERY BSP Driver
[32f401cdiscovery-bsp](https://github.com/STMicroelectronics/32f401cdiscovery-bsp)         | 32F401CDISCOVERY BSP Driver
[stm32446e-eval-bsp](https://github.com/STMicroelectronics/stm32446e-eval-bsp)             | STM32446E-EVAL BSP Driver
[32f411ediscovery-bsp](https://github.com/STMicroelectronics/32f411ediscovery-bsp)         | 32F411EDISCOVERY BSP Driver
[32f412gdiscovery-bsp](https://github.com/STMicroelectronics/32f412gdiscovery-bsp)         | 32F412GDISCOVERY BSP Driver
[32f413hdiscovery-bsp](https://github.com/STMicroelectronics/32f413hdiscovery-bsp)         | 32F413HDISCOVERY BSP Driver
[stm32f4-discovery-bsp](https://github.com/STMicroelectronics/stm32f4-discovery-bsp)       | STM32F4-Discovery BSP Driver
[stm324x9i-eval-bsp](https://github.com/STMicroelectronics/stm324x9i-eval-bsp)             | STM324x9I-EVAL BSP Driver

STM32CubeF7 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32756g-eval-bsp](https://github.com/STMicroelectronics/stm32756g-eval-bsp)             | STM32756G_EVAL BSP Driver
[stm32f7308-dk-bsp](https://github.com/STMicroelectronics/stm32f7308-dk-bsp)               | STM32F7308-Discovery BSP Driver
[stm32f7508-dk-bsp](https://github.com/STMicroelectronics/stm32f7508-dk-bsp)               | STM32F7508-Discovery BSP Driver
[stm32f769i-eval-bsp](https://github.com/STMicroelectronics/stm32f769i-eval-bsp)           | STM32F769I_EVAL BSP Driver
[stm32f7xx-nucleo-144-bsp](https://github.com/STMicroelectronics/stm32f7xx-nucleo-144-bsp) | F7 nucleo BSP Driver
[32f769idiscovery-bsp](https://github.com/STMicroelectronics/32f769idiscovery-bsp)         | 32F769IDISCOVERY BSP Driver
[32f723ediscovery-bsp](https://github.com/STMicroelectronics/32f723ediscovery-bsp)         | 32F723EDISCOVERY BSP Driver
[32f746gdiscovery-bsp](https://github.com/STMicroelectronics/32f746gdiscovery-bsp)         | 32F746GDISCOVERY BSP Driver

STM32CubeG0 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32g0316-disco-bsp](https://github.com/STMicroelectronics/stm32g0316-disco-bsp)       | STM32G0316-DISCO BSP Driver
[stm32g071b-disco-bsp](https://github.com/STMicroelectronics/stm32g071b-disco-bsp)       | STM32G071B-DISCO BSP Driver
[stm32g081b-eval-bsp](https://github.com/STMicroelectronics/stm32g081b-eval-bsp)         | STM32G081B_EVAL BSP Driver
[stm32g0c1e-ev-bsp](https://github.com/STMicroelectronics/stm32g0c1e-ev-bsp)             | STM32G0C1E-EV BSP Driver
[stm32g0xx-nucleo-bsp](https://github.com/STMicroelectronics/stm32g0xx-nucleo-bsp)       | G0 nucleo BSP Driver
[stm32g0xx-nucleo-32-bsp](https://github.com/STMicroelectronics/stm32g0xx-nucleo-32-bsp) | G0 nucleo BSP Driver

STM32CubeG4 BSP Boards Drivers | Description
-------------------------------|-------------
[b-g474e-dpow1-bsp](https://github.com/STMicroelectronics/b-g474e-dpow1-bsp)       | B-G474E-DPOW1 BSP Driver
[stm32g474e-eval-bsp](https://github.com/STMicroelectronics/stm32g474e-eval-bsp)   | STM32G474E-EVAL BSP Driver
[stm32g4xx-nucleo-bsp](https://github.com/STMicroelectronics/stm32g4xx-nucleo-bsp) | G4 nucleo BSP Driver

STM32CubeH5 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32h573i-discovery-bsp](https://github.com/STMicroelectronics/stm32h573i-discovery-bsp) | STM32H573I-DK BSP Driver
[stm32h5xx-nucleo-bsp](https://github.com/STMicroelectronics/stm32h5xx-nucleo-bsp)         | H5 nucleo BSP Driver

STM32CubeH7 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32h7b3i-dk-bsp](https://github.com/STMicroelectronics/stm32h7b3i-dk-bsp)       | STM32H7B3I-DK BSP Driver
[stm32h750b-dk-bsp](https://github.com/STMicroelectronics/stm32h750b-dk-bsp)       | STM32H750B-DK BSP Driver
[stm32h747i-eval-bsp](https://github.com/STMicroelectronics/stm32h747i-eval-bsp)   | STM32H747I-EVAL BSP Driver
[stm32h747i-disco-bsp](https://github.com/STMicroelectronics/stm32h747i-disco-bsp) | STM32H747I-DISCO BSP Driver
[stm32h745i-disco-bsp](https://github.com/STMicroelectronics/stm32h745i-disco-bsp) | STM32H745I-DISCO BSP Driver
[stm32h743i-eval-bsp](https://github.com/STMicroelectronics/stm32h743i-eval-bsp)   | STM32H743I-EVAL BSP Driver
[stm32h735g-dk-bsp](https://github.com/STMicroelectronics/stm32h735g-dk-bsp)       | STM32H735G-DK BSP Driver
[stm32h7b3i-eval-bsp](https://github.com/STMicroelectronics/stm32h7b3i-eval-bsp)   | STM32H7B3I-EVAL BSP Driver
[stm32h7xx-nucleo-bsp](https://github.com/STMicroelectronics/stm32h7xx-nucleo-bsp) | H7 nucleo BSP Driver

STM32CubeL0 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32l073z-eval-bsp](https://github.com/STMicroelectronics/stm32l073z-eval-bsp)         | STM32L073Z-EVAL BSP Driver
[stm32l0xx-nucleo-bsp](https://github.com/STMicroelectronics/stm32l0xx-nucleo-bsp)       | L0 nucleo BSP Driver
[stm32l0xx-nucleo-32-bsp](https://github.com/STMicroelectronics/stm32l0xx-nucleo-32-bsp) | L0 nucleo 32 BSP Driver
[32l0538discovery-bsp](https://github.com/STMicroelectronics/32l0538discovery-bsp)       | 32L100CDISCOVERY BSP Driver

STM32CubeL1 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32l152d-eval-bsp](https://github.com/STMicroelectronics/stm32l152d-eval-bsp)   | STM32L152D-EVAL BSP Driver
[stm32l1xx-nucleo-bsp](https://github.com/STMicroelectronics/stm32l1xx-nucleo-bsp) | L1 nucleo BSP Driver
[32l152cdiscovery-bsp](https://github.com/STMicroelectronics/32l152cdiscovery-bsp) | 32L152CDISCOVERY BSP Driver
[32l100cdiscovery-bsp](https://github.com/STMicroelectronics/32l100cdiscovery-bsp) | 32L100CDISCOVERY BSP Driver

STM32CubeL4 BSP Boards Drivers | Description
-------------------------------|-------------
[b-l475e-iot01a-bsp](https://github.com/STMicroelectronics/b-l475e-iot01a-bsp)             | B-L475E-IOT01A BSP Driver
[b-l4s5i-iot01a-bsp](https://github.com/STMicroelectronics/b-l4s5i-iot01a-bsp)             | B-L4S5I-IOT01A BSP Driver
[stm32l476g-eval-bsp](https://github.com/STMicroelectronics/stm32l476g-eval-bsp)           | STM32L476G-EVAL BSP Driver
[stm32l4p5g-dk-bsp](https://github.com/STMicroelectronics/stm32l4p5g-dk-bsp)               | STM32L4P5G-DK BSP Driver
[stm32l4r9i-eval-bsp](https://github.com/STMicroelectronics/stm32l4r9i-eval-bsp)           | STM32L4R9I-EVAL BSP Driver
[stm32l4xx-nucleo-bsp](https://github.com/STMicroelectronics/stm32l4xx-nucleo-bsp)         | L4 nucleo BSP Driver
[stm32l4xx-nucleo-144-bsp](https://github.com/STMicroelectronics/stm32l4xx-nucleo-144-bsp) | L4 nucleo 144 BSP Driver
[stm32l4xx-nucleo-32-bsp](https://github.com/STMicroelectronics/stm32l4xx-nucleo-32-bsp)   | L4 nucleo 32 BSP Driver
[32l496gdiscovery-bsp](https://github.com/STMicroelectronics/32l496gdiscovery-bsp)         | 32L496GDISCOVERY BSP Driver
[32l4r9idiscovery-bsp](https://github.com/STMicroelectronics/32l4r9idiscovery-bsp)         | 32L4R9IDISCOVERY BSP Driver
[32l476gdiscovery-bsp](https://github.com/STMicroelectronics/32l476gdiscovery-bsp)         | 32L476GDISCOVERY BSP Driver

STM32CubeL5 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32l562e-dk-bsp](https://github.com/STMicroelectronics/stm32l562e-dk-bsp)       | STM32L562E-DK BSP Driver
[stm32l552e-ev-bsp](https://github.com/STMicroelectronics/stm32l552e-ev-bsp)       | STM32L552E-EV BSP Driver
[stm32l5xx-nucleo-bsp](https://github.com/STMicroelectronics/stm32l5xx-nucleo-bsp) | L5 nucleo BSP Driver

STM32CubeU5 BSP Boards Drivers | Description
-------------------------------|-------------
[b-u585i-iot02a-bsp](https://github.com/STMicroelectronics/b-u585i-iot02a-bsp)     | B-U585I-IOT02A BSP Driver
[stm32u575i-ev-bsp](https://github.com/STMicroelectronics/stm32u575i-ev-bsp)       | STM32U575I-EV BSP Driver
[stm32u5x9j-dk-bsp](https://github.com/STMicroelectronics/stm32u5x9j-dk-bsp)       | STM32U5A9J-DK and STM32U5G9J-DK1 BSP Driver
[stm32u5g9j-dk2-bsp](https://github.com/STMicroelectronics/stm32u5g9j-dk2-bsp)     | STM32U5G9J-DK2 BSP Driver
[stm32u5xx-nucleo-bsp](https://github.com/STMicroelectronics/stm32u5xx-nucleo-bsp) | U5 nucleo BSP Driver

STM32CubeWB BSP Boards Drivers | Description
-------------------------------|-------------
[stm32wb5mm-dk-bsp](https://github.com/STMicroelectronics/stm32wb5mm-dk-bsp)                       | STM32WB5MM-DK BSP Driver
[nucleo-wb15cc-bsp](https://github.com/STMicroelectronics/nucleo-wb15cc-bsp)                       | NUCLEO-WB15CC BSP Driver
[p-nucleo-wb55-nucleo-bsp](https://github.com/STMicroelectronics/p-nucleo-wb55-nucleo-bsp)         | P-NUCLEO-WB55.Nucleo BSP Driver
[p-nucleo-wb55-usb-dongle-bsp](https://github.com/STMicroelectronics/p-nucleo-wb55-usb-dongle-bsp) | P-NUCLEO-WB55.USBDongle BSP Driver

STM32CubeWBA BSP Boards Drivers | Description
-------------------------------|-------------
[stm32wbaxx-nucleo-bsp](https://github.com/STMicroelectronics/stm32wbaxx-nucleo-bsp) | WBA nucleo BSP Driver

STM32CubeWL BSP Boards Drivers | Description
-------------------------------|-------------
[stm32wlxx-nucleo-bsp](https://github.com/STMicroelectronics/stm32wlxx-nucleo-bsp) | WL nucleo BSP Driver

### STM32Cube BSP Components Drivers

STM32Cube BSP Audio Components Drivers | Description
-------------------------------------- | -----------
[stm32-adv7533](https://github.com/STMicroelectronics/stm32-adv7533) | The ADV7533 BSP Component Driver
[stm32-ak4343](https://github.com/STMicroelectronics/stm32-ak4343)   | The AK4343 BSP Component Driver
[stm32-cs42l51](https://github.com/STMicroelectronics/stm32-cs42l51) | The CS42L51 BSP Component Driver
[stm32-cs42l52](https://github.com/STMicroelectronics/stm32-cs42l52) | The CS42L52 BSP Component Driver
[stm32-cs43l22](https://github.com/STMicroelectronics/stm32-cs43l22) | The CS43L22 BSP Component Driver
[stm32-wm8994](https://github.com/STMicroelectronics/stm32-wm8994)   | The WM8994 BSP Component Driver

STM32Cube BSP Camera Components Drivers | Description
--------------------------------------- | -----------
[stm32-ov2640](https://github.com/STMicroelectronics/stm32-ov2640)   | The OV2640 BSP Component Driver
[stm32-ov5640](https://github.com/STMicroelectronics/stm32-ov5640)   | The OV5640 BSP Component Driver
[stm32-ov9655](https://github.com/STMicroelectronics/stm32-ov9655)   | The OV9655 BSP Component Driver
[stm32-s5k5cag](https://github.com/STMicroelectronics/stm32-s5k5cag) | The S5K5CAG BSP Component Driver

STM32Cube BSP IO Expander Components Drivers | Description
-------------------------------------------- | -----------
[stm32-mfxstm32l152](https://github.com/STMicroelectronics/stm32-mfxstm32l152) | The MFXSTM32L152 BSP Component Driver
[stm32-stmpe1600](https://github.com/STMicroelectronics/stm32-stmpe1600)       | The STMPE1600 BSP Component Driver
[stm32-stmpe811](https://github.com/STMicroelectronics/stm32-stmpe811)         | The STMPE811 BSP Component Driver

STM32Cube BSP LCD Components Drivers | Description
------------------------------------ | -----------
[stm32-ampire480272](https://github.com/STMicroelectronics/stm32-ampire480272) | The AMPIRE480272 BSP Component Driver
[stm32-ampire640480](https://github.com/STMicroelectronics/stm32-ampire640480) | The AMPIRE640480 BSP Component Driver
[stm32-hx8347d](https://github.com/STMicroelectronics/stm32-hx8347d)           | The HX8347D BSP Component Driver
[stm32-hx8347g](https://github.com/STMicroelectronics/stm32-hx8347g)           | The HX8347G BSP Component Driver
[stm32-hx8347i](https://github.com/STMicroelectronics/stm32-hx8347i)           | The HX8347I BSP Component Driver
[stm32-ili9320](https://github.com/STMicroelectronics/stm32-ili9320)           | The ILI9320 BSP Component Driver
[stm32-ili9325](https://github.com/STMicroelectronics/stm32-ili9325)           | The ILI9325 BSP Component Driver
[stm32-ili9328](https://github.com/STMicroelectronics/stm32-ili9328)           | The ILI9328 BSP Component Driver
[stm32-ili9341](https://github.com/STMicroelectronics/stm32-ili9341)           | The ILI9341 BSP Component Driver
[stm32-ls016b8uy](https://github.com/STMicroelectronics/stm32-ls016b8uy)       | The LS016B8UY BSP Component Driver
[stm32-nt35510](https://github.com/STMicroelectronics/stm32-nt35510)           | The NT35510 BSP Component Driver
[stm32-otm8009a](https://github.com/STMicroelectronics/stm32-otm8009a)         | The OTM8009A BSP Component Driver
[stm32-rk043fn48h](https://github.com/STMicroelectronics/stm32-rk043fn48h)     | The RK043FN48H BSP Component Driver
[stm32-rk070er9427](https://github.com/STMicroelectronics/stm32-rk070er9427)   | The RK070ER9427 BSP Component Driver
[stm32-spfd5408](https://github.com/STMicroelectronics/stm32-spfd5408)         | The SPFD5408 BSP Component Driver
[stm32-ssd1315](https://github.com/STMicroelectronics/stm32-ssd1315)           | The SSD1315 BSP Component Driver
[stm32-st7735](https://github.com/STMicroelectronics/stm32-st7735)             | The ST7735 BSP Component Driver
[stm32-st7789h2](https://github.com/STMicroelectronics/stm32-st7789h2)         | The ST7789H2 BSP Component Driver

STM32Cube BSP MEMS Components Drivers | Description
------------------------------------- | -----------
[stm32-hts221](https://github.com/STMicroelectronics/stm32-hts221)         | The HTS221 BSP Component Driver
[stm32-ism330dhcx](https://github.com/STMicroelectronics/stm32-ism330dhcx) | The ISM330DHCX BSP Component Driver
[stm32-ism330dlc](https://github.com/STMicroelectronics/stm32-ism330dlc)   | The ISM330DLC BSP Component Driver
[stm32-i3g4250d](https://github.com/STMicroelectronics/stm32-i3g4250d)     | The I3G4250D BSP Component Driver
[stm32-l3gd20](https://github.com/STMicroelectronics/stm32-l3gd20)         | The L3GD20 BSP Component Driver
[stm32-lan8742](https://github.com/STMicroelectronics/stm32-lan8742)       | The LAN8742 BSP Component Driver
[stm32-lis302dl](https://github.com/STMicroelectronics/stm32-lis302dl)     | The LIS302DL BSP Component Driver
[stm32-lis3dsh](https://github.com/STMicroelectronics/stm32-lis3dsh)       | The LIS3DSH BSP Component Driver
[stm32-lis3mdl](https://github.com/STMicroelectronics/stm32-lis3mdl)       | The LIS3MDL BSP Component Driver
[stm32-lps22hb](https://github.com/STMicroelectronics/stm32-lps22hb)       | The LPS22HB BSP Component Driver
[stm32-lps22hh](https://github.com/STMicroelectronics/stm32-lps22hh)       | The LPS22HH BSP Component Driver
[stm32-lsm303agr](https://github.com/STMicroelectronics/stm32-lsm303agr)   | The LSM303AGR BSP Component Driver
[stm32-lsm303c](https://github.com/STMicroelectronics/stm32-lsm303c)       | The LSM303C BSP Component Driver
[stm32-lsm303dlhc](https://github.com/STMicroelectronics/stm32-lsm303dlhc) | The LSM303DLHC BSP Component Driver
[stm32-lsm6dsl](https://github.com/STMicroelectronics/stm32-lsm6dsl)       | The LSM6DSL BSP Component Driver
[stm32-s70kl1281](https://github.com/STMicroelectronics/stm32-s70kl1281)   | The S70KL1281 BSP Component Driver

STM32Cube BSP Magnetometer Components Drivers | Description
------------------------------------- | -----------
[stm32-iis2mdc](https://github.com/STMicroelectronics/stm32-iis2mdc)       | The IIS2mdc BSP Component Driver

STM32Cube BSP QSPI/OSPI Components Drivers | Description
------------------------------------------ | -----------
[stm32-iss66wvh8m8](https://github.com/STMicroelectronics/stm32-iss66wvh8m8)   | The ISS66WVH8M8 BSP Component Driver
[stm32-mt25ql512abb](https://github.com/STMicroelectronics/stm32-mt25ql512abb) | The MT25QL512ABB BSP Component Driver
[stm32-mt25tl01g](https://github.com/STMicroelectronics/stm32-mt25tl01g)       | The MT25TL01G BSP Component Driver
[stm32-mx25l512](https://github.com/STMicroelectronics/stm32-mx25l512)         | The MX25L512 BSP Component Driver
[stm32-mx25lm51245g](https://github.com/STMicroelectronics/stm32-mx25lm51245g) | The MX25LM51245G BSP Component Driver
[stm32-mx25r6435f](https://github.com/STMicroelectronics/stm32-mx25r6435f)     | The MX25R6435F BSP Component Driver
[stm32-n25q128a](https://github.com/STMicroelectronics/stm32-n25q128a)         | The N25Q128A BSP Component Driver
[stm32-n25q256a](https://github.com/STMicroelectronics/stm32-n25q256a)         | The N25Q256A BSP Component Driver
[stm32-n25q512a](https://github.com/STMicroelectronics/stm32-n25q512a)         | The N25Q512A BSP Component Driver
[stm32-s25fl128s](https://github.com/STMicroelectronics/stm32-s25fl128s)       | The S25FL128S BSP Component Driver
[stm32-s25fl512s](https://github.com/STMicroelectronics/stm32-s25fl512s)       | The S25FL512S BSP Component Driver

STM32Cube BSP SDRAM Components Drivers | Description
-------------------------------------- | -----------
[stm32-is42s16800j](https://github.com/STMicroelectronics/stm32-is42s16800j)   | The IS42S16800J BSP Component Driver
[stm32-is42s32800g](https://github.com/STMicroelectronics/stm32-is42s32800g)   | The IS42S32800G BSP Component Driver
[stm32-is42s32800j](https://github.com/STMicroelectronics/stm32-is42s32800j)   | The IS42S32800J BSP Component Driver
[stm32-mt48lc4m32b2](https://github.com/STMicroelectronics/stm32-mt48lc4m32b2) | The MT48LC4M32B2 BSP Component Driver

STM32Cube BSP Temperature Sensor Components Drivers | Description
--------------------------------------------------- | -----------
[stm32-stlm75](https://github.com/STMicroelectronics/stm32-stlm75)   | The STLM75 BSP Component Driver
[stm32-stts22h](https://github.com/STMicroelectronics/stm32-stts22h) | The STTS22H BSP Component Driver
[stm32-stts751](https://github.com/STMicroelectronics/stm32-stts751) | The STTS751 BSP Component Driver

STM32Cube BSP Touch Screen Components Drivers | Description
-------------------------------------- | -----------
[stm32-cy8c4014lqi](https://github.com/STMicroelectronics/stm32-cy8c4014lqi) | The CY8C4014LQI BSP Component Driver
[stm32-exc7200](https://github.com/STMicroelectronics/stm32-exc7200)         | The EXC7200 BSP Component Driver
[stm32-ft3x67](https://github.com/STMicroelectronics/stm32-ft3x67)           | The FT3X67 BSP Component Driver
[stm32-ft6x06](https://github.com/STMicroelectronics/stm32-ft6x06)           | The FT6X06 BSP Component Driver
[stm32-ft5336](https://github.com/STMicroelectronics/stm32-ft5336)           | The FT5336 BSP Component Driver
[stm32-ts3510](https://github.com/STMicroelectronics/stm32-ts3510)           | The TS3510 BSP Component Driver

STM32Cube BSP USB-C Components Drivers | Description
-------------------------------------- | -----------
[stm32-cbtl08gp053](https://github.com/STMicroelectronics/stm32-cbtl08gp053) | The CBTL08GP053 BSP Component Driver
[stm32-sn65dp141](https://github.com/STMicroelectronics/stm32-sn65dp141)     | The SN65DP141 BSP Component Driver
[stm32-tusb546](https://github.com/STMicroelectronics/stm32-tusb546)         | The TUSB546 BSP Component Driver

STM32Cube BSP miscellaneous Components Drivers | Description
---------------------------------------------- | -----------
[stm32-gde021a1](https://github.com/STMicroelectronics/stm32-gde021a1) | The GDE021A1 BSP Component Driver
[stm32-m24lr64](https://github.com/STMicroelectronics/stm32-m24lr64)   | The M24LR64 BSP Component Driver
[stm32-m24sr](https://github.com/STMicroelectronics/stm32-m24sr)       | The M24SR BSP Component Driver
[stm32-ina230](https://github.com/STMicroelectronics/stm32-ina230)     | The INA230 BSP Component Driver

### STM32Cube Middleware Libraries and Applications

STM32Cube Classic Core MW Libraries | Description
----------------------------------- | -----------
[stm32_mw_fatfs](https://github.com/STMicroelectronics/stm32_mw_fatfs)           | FatFS middleware library
[stm32_mw_freertos](https://github.com/STMicroelectronics/stm32_mw_freertos)     | FreeRTOS middleware library
[stm32_mw_lwip](https://github.com/STMicroelectronics/stm32_mw_lwip)             | LwIP middleware library
[stm32_mw_openbl](https://github.com/STMicroelectronics/stm32-mw-openbl)         | Open Bootloader middleware library
[stm32_mw_usb_device](https://github.com/STMicroelectronics/stm32_mw_usb_device) | USB Device middleware library
[stm32_mw_usb_host](https://github.com/STMicroelectronics/stm32_mw_usb_host)     | USB Host middleware library

STM32Cube Azure RTOS MW Libraries | Description
--------------------------------- | -----------
[stm32_mw_cmsis_rtos_tx](https://github.com/STMicroelectronics/stm32_mw_cmsis_rtos_tx) | CMSIS-RTOS wrapper for Azure RTOS ThreadX library
[stm32_mw_filex](https://github.com/STMicroelectronics/stm32_mw_filex)                 | Azure RTOS FileX library
[stm32_mw_levelx](https://github.com/STMicroelectronics/stm32_mw_levelx)               | Azure RTOS LevelX library
[stm32_mw_netxduo](https://github.com/STMicroelectronics/stm32_mw_netxduo)             | Azure RTOS NetX Duo library
[stm32_mw_threadx](https://github.com/STMicroelectronics/stm32_mw_threadx)             | Azure RTOS ThreadX library
[stm32_mw_usbx](https://github.com/STMicroelectronics/stm32_mw_usbx)                   | Azure RTOS USBX library

STM32Cube Classic Core MW Applications | Description
-------------------------------------- | -----------
[stm32h5-classic-coremw-apps](https://github.com/STMicroelectronics/stm32h5-classic-coremw-apps) | Applications based on ST USB Device, ST USB Host, FatFS, and LwIP libraries for STM32H5 series. 
[stm32u5-classic-coremw-apps](https://github.com/STMicroelectronics/stm32u5-classic-coremw-apps) | Applications based on ST USB Device, ST USB Host, and FreeRTOS libraries for STM32U5 series. 

STM32Cube Open Bootloader MW Applications | Description
----------------------------------------- | -----------
[stm32l5-openbl-apps](https://github.com/STMicroelectronics/stm32l5-openbl-apps)                 | Applications based on the Open Bootloader library for STM32L5 series. 
[stm32wb-openbl-apps](https://github.com/STMicroelectronics/stm32wb-openbl-apps)                 | Applications based on the Open Bootloader library for STM32WB series. 
[stm32wl-openbl-apps](https://github.com/STMicroelectronics/stm32wl-openbl-apps)                 | Applications based on the Open Bootloader library for STM32WL series. 

### STM32Cube Utilities and Miscellaneous repos

Repository          | Description
------------------- | -----------
[stm32-external-loader](https://github.com/STMicroelectronics/stm32-external-loader) | Flashloaders source code of external memories embedded in the STM32 HW boards.
[stm32ai](https://github.com/STMicroelectronics/stm32ai)                             | Open source AI offer in STM32 products.
[STM32_open_pin_data](https://github.com/STMicroelectronics/STM32_open_pin_data)     | This repo provides all the information required for the pin and board configuration of products based on STM32 MCU.
