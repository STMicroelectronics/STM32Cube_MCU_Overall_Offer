# STM32Cube MCU Overall Offer

## Overview

**STM32Cube** is an STMicroelectronics original initiative to ease the developers life by reducing efforts, time and cost.

**STM32Cube** covers the overall STM32 products portfolio (MCU and MPU). It includes a comprehensive embedded software platform, delivered for each STM32 series.

* The CMSIS modules (core and device) corresponding to the ARM(tm) core implemented in this STM32 product.
* The STM32 HAL-LL drivers : an abstraction drivers layer, the API ensuring maximized portability across the STM32 portfolio.
* The BSP Drivers of each evaluation or demonstration board provided by this STM32 series.
* A consistent set of middlewares components such as RTOS, USB, FatFS, Graphics, TCP/IP, BLE, STM32_TouchSensing_Library...
* A full set of software projects (basic examples, applications or demonstrations) for each board provided by this STM32 series.

GitHub is a new publication model for the STM32Cube MCU embedded software. Three models of publication are proposed:

* The **MCU Package** : monolithic STM32Cube software modules, per STM32 MCU series (Drivers, Middlewares, Utilities, Examples Projects) in an unique repo. The usual name of a STM32MCU Package is **STM32Cubexx**, xx corresponding to the STM32 series). Please refer to the chapter **STM32Cube MCU Packages** below.

* The **MCU components** : parts of the MCU Packages, proposed as individual repos, allowing the user to select and get only the required software functions. Please refer to the chapter **STM32Cube MCU Components** below.

* The **X-CUBE** : Expansion softwares, propose embedded software components that complement the functionalities of the STM32Cube.

* A set of **MCU Utilities** : Various Utility features proposed in dedicated repos.

Please note that a MPU offer is also proposed for the **STM32 MPU Products**. You can refer to the repo [STM32MPU_EmbSW_Overall_Offer](https://github.com/STMicroelectronics/STM32MPU_EmbSW_Overall_Offer).

## Description

This repo is a simple Readme describing all STM32 MCU related GitHub projects, the overall offer for the STM32 MCU products.

This new publication channel of the STM32Cube embedded software components will provide new added values :

* In complement to the MCU Package zip files today proposed on **st.com**, the capability for STM32 customers to get a configuration management based delivery (Git)
* A more direct communication between developers, thanks to the Issues features. **Caution** : only software related questions will be taken into account. Any other subject must be submitted to the [ST Community](https://community.st.com/stm32mcu) forum
* Thanks to the deployment of a Contributor License Agreement feature (please refer to each repo CONTRIBUTING guide), the **Pull-Request** permits also to take into account customers proposed updates and enrich the STM32Cube FW offer.

For general communication and support, you can use

* [ST Support Center](https://my.st.com/ols#/ols/) for any defect
* [ST Community Forum](https://community.st.com/stm32mcu) forum

## Content

* [STM32Cube MCU Packages](README.md#stm32cube-mcu-packages)
* [STM32Cube X-CUBE](README.md#x-cube-expansion-softwares)
* [STM32Cube Function Packs](README.md#fp-function-packs)
* [STM32Cube CMSIS](README.md#stm32cube-cmsis)
* [STM32Cube HAL Drivers](README.md#stm32cube-hal-drivers)
* [STM32Cube BSP Drivers](README.md#stm32cube-bsp-drivers)
* [STM32Cube MW Libraries](README.md#stm32cube-middleware-libraries)
* [STM32Cube Utilities and miscellaneous](README.md#stm32cube-utilities-and-miscellaneous-repos)

## STM32Cube MCU Packages

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
[STM32CubeU5](https://github.com/STMicroelectronics/STM32CubeU5) | The STM32CubeU5 FW MCU Package
[STM32CubeWB](https://github.com/STMicroelectronics/STM32CubeWB) | The STM32CubeWB FW MCU Package
[STM32CubeWL](https://github.com/STMicroelectronics/STM32CubeWL) | The STM32CubeWL FW MCU Package

## X-CUBE Expansion softwares

The STM32Cube expansion software contains embedded software components that complement the functionalities of the STM32Cube and/or enable the usage of a multitude of ST devices in domains such as of sensing, power management, connectivity or audio, together with the most appropriate STM32 MCUs.

STM32Cube X-CUBE | Description
---------------- | -----------
[x-cube-aws](https://github.com/STMicroelectronics/x-cube-aws)             | AWS IoT Expansion Package for STM32Cube.
[x-cube-azrtos-f4](https://github.com/STMicroelectronics/x-cube-azrtos-f4) | Azure RTOS Expansion Package for STM32Cube, for STM32F4 series.
[x-cube-azrtos-f7](https://github.com/STMicroelectronics/x-cube-azrtos-f7) | Azure RTOS Expansion Package for STM32Cube, for STM32F7 series.
[x-cube-azrtos-g0](https://github.com/STMicroelectronics/x-cube-azrtos-g0) | Azure RTOS Expansion Package for STM32Cube, for STM32G0 series.
[x-cube-azrtos-g4](https://github.com/STMicroelectronics/x-cube-azrtos-g4) | Azure RTOS Expansion Package for STM32Cube, for STM32G4 series.
[x-cube-azrtos-h7](https://github.com/STMicroelectronics/x-cube-azrtos-h7) | Azure RTOS Expansion Package for STM32Cube, for STM32H7 series.
[x-cube-azrtos-l4](https://github.com/STMicroelectronics/x-cube-azrtos-l4) | Azure RTOS Expansion Package for STM32Cube, for STM32L4 series.
[x-cube-azrtos-l5](https://github.com/STMicroelectronics/x-cube-azrtos-l5) | Azure RTOS Expansion Package for STM32Cube, for STM32L5 series.
[x-cube-azrtos-wb](https://github.com/STMicroelectronics/x-cube-azrtos-wb) | Azure RTOS Expansion Package for STM32Cube, for STM32WB series.
[x-cube-azrtos-wl](https://github.com/STMicroelectronics/x-cube-azrtos-wl) | Azure RTOS Expansion Package for STM32Cube, for STM32WL series.
[x-cube-ble1](https://github.com/STMicroelectronics/x-cube-ble1)           | BlueNRG-M0 Bluetooth Low Energy Expansion Package for STM32Cube.
[x-cube-ble2](https://github.com/STMicroelectronics/X-CUBE-BLE2)           | BlueNRG-2 Bluetooth Low Energy Expansion Package for STM32Cube.
[x-cube-eeprma1](https://github.com/STMicroelectronics/X-CUBE-EEPRMA1)     | M24XX I2C and M95XX SPI EEPROMs Expansion Package for STM32Cube.
[x-cube-iota1](https://github.com/STMicroelectronics/X-CUBE-IOTA1)         | IOTA Distributed Ledger Technology Expansion Package for STM32Cube.
[x-cube-mems1](https://github.com/STMicroelectronics/x-cube-mems1)         | X-CUBE-MEMS1 Expansion Package for STM32Cube. (X-NUCLEO-IKS01A2, X-NUCLEO-IKS01A3 and X-NUCLEO-IKS02A1)
[x-cube-nfc4](https://github.com/STMicroelectronics/X-CUBE-NFC4)           | Dynamic NFC/RFID tag IC (ST25DV device) Expansion Package for STM32Cube.
[x-cube-subg2](https://github.com/STMicroelectronics/x-cube-subg2)         | Sub 1 GHz RF communication for S2-LP Expansion Package for STM32Cube.
[x-cube-tcpp](https://github.com/STMicroelectronics/x-cube-tcpp)           | USB-IF certified Expansion Package for the integration of TCPPs protection circuits (OV/OC).
[x-cube-usb-pd](https://github.com/STMicroelectronics/x-cube-usb-pd)       | USB-IF certified Expansion Package as USB Type-C port manager (TCPM).

## FP Function Packs

STM32 Function Packs are a combination of low-level drivers, middleware libraries and sample applications assembled into a single software package.

You can get the entire list of available Function Packs on st.com: [STM32 ODE Function Packs](https://www.st.com/en/ecosystems/stm32-ode-function-packs.html).

The below list represents the Function Packs available on GitHub.com

STM32Cube Function Packs | Description
------------------------ | -----------
[fp-sns-motenv1](https://github.com/STMicroelectronics/FP-SNS-MOTENV1)     | STM32Cube function pack for IoT node with BLE connectivity and environmental and motion sensors.
[fp-sns-flight1](https://github.com/STMicroelectronics/fp-sns-flight1)     | STM32Cube function pack for IoT node with BLE connectivity to view real-time time-of-flight sensors data.

## STM32Cube MCU Components

As mentioned above, the STM32Cube Components is an alternative delivery model to the STM32 Packages. In this case, each module is delivered as individual repos, allowing the customer to select and download only the pertinent features.

* Components available today : CMSIS - HAL/LL - Base MW (USB, FatFS, FrreRTOS, LwIP)
* Components upcoming : Other MW - BSP - Utilities

In each module README file you will find the cross compatibility information. When all modules will be available a set of new Manifest files (series by series) will be proposed to drive the user.

### STM32Cube CMSIS

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
[cmsis_device_u5](https://github.com/STMicroelectronics/cmsis_device_u5) | The STM32U5 CMSIS Device files
[cmsis_device_wb](https://github.com/STMicroelectronics/cmsis_device_wb) | The STM32WB CMSIS Device files
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
[stm32u5xx_hal_driver](https://github.com/STMicroelectronics/stm32u5xx_hal_driver) | The STM32U5 HAL-LL Drivers
[stm32wbxx_hal_driver](https://github.com/STMicroelectronics/stm32wbxx_hal_driver) | The STM32WB HAL-LL Drivers
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

STM32CubeF0 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32f0xx-nucleo-32](https://github.com/STMicroelectronics/stm32f0xx-nucleo-32) | F0 nucleo 32 BSP Driver
[stm32f0xx-nucleo](https://github.com/STMicroelectronics/stm32f0xx-nucleo) | F0 nucleo BSP Driver
[stm32091c-eval](https://github.com/STMicroelectronics/stm32091c-eval) | STM32091C_EVAL BSP Driver
[stm32072b-eval](https://github.com/STMicroelectronics/stm32072b-eval) | STM32072B_EVAL BSP Driver
[32f072bdiscovery](https://github.com/STMicroelectronics/32f072bdiscovery) | 32F072BDISCOVERY BSP Driver
[32f0308discovery](https://github.com/STMicroelectronics/32f0308discovery) | 32F0308DISCOVERY BSP Driver

STM32CubeF1 BSP Boards Drivers | Description
-------------------------------|-------------
[stm3210c-eval](https://github.com/STMicroelectronics/stm3210c-eval) | STM3210C_EVAL BSP Driver
[stm3210e-eval](https://github.com/STMicroelectronics/stm3210e-eval) | STM3210E_EVAL BSP Driver
[stm32f1xx-nucleo](https://github.com/STMicroelectronics/stm32f1xx-nucleo) | F1 nucleo BSP Driver
[stm32vldiscovery](https://github.com/STMicroelectronics/stm32vldiscovery) | STM32VLDISCOVERY BSP Driver

STM32CubeF2 BSP Boards Drivers | Description
-------------------------------|-------------
[stm322xg-eval](https://github.com/STMicroelectronics/stm322xg-eval) | STM322xG_EVAL BSP Driver
[stm32f2xx-nucleo-144](https://github.com/STMicroelectronics/stm32f2xx-nucleo-144) | F2 nucleo BSP Driver

STM32CubeF3 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32303c-eval](https://github.com/STMicroelectronics/stm32303c-eval) | STM32303C_EVAL BSP Driver
[stm32303e-eval](https://github.com/STMicroelectronics/stm32303e-eval) | STM32303E_EVAL BSP Driver
[stm32373c-eval](https://github.com/STMicroelectronics/stm32373c-eval) | STM32373C_EVAL BSP Driver
[stm32f3discovery](https://github.com/STMicroelectronics/stm32f3discovery) | STM32F3-Discovery BSP Driver
[stm32f3xx-nucleo](https://github.com/STMicroelectronics/stm32f3xx-nucleo) | F3 nucleo BSP Driver
[stm32f3xx-nucleo-144](https://github.com/STMicroelectronics/stm32f3xx-nucleo-144) | F3 nucleo 144 BSP Driver
[stm32f3xx-nucleo-32](https://github.com/STMicroelectronics/stm32f3xx-nucleo-32) | F3 nucleo 32 BSP Driver
[32f3348discovery](https://github.com/STMicroelectronics/32f3348discovery) | 32F3348DISCOVERY BSP Driver

STM32CubeF4 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32f4xx-nucleo-144](https://github.com/STMicroelectronics/stm32f4xx-nucleo-144) | F4 nucleo 144 BSP Driver
[stm32f4xx-nucleo](https://github.com/STMicroelectronics/stm32f4xx-nucleo) | F4 nucleo BSP Driver
[stm324xg-eval](https://github.com/STMicroelectronics/stm324xg-eval) | STM324xG_EVAL BSP Driver
[stm32469i-eval](https://github.com/STMicroelectronics/stm32469i-eval) | STM32469I_EVAL BSP Driver
[stm32469i-discovery](https://github.com/STMicroelectronics/stm32469i-discovery) | STM32469I-Discovery BSP Driver
[stm32f429i-discovery](https://github.com/STMicroelectronics/stm32f429i-discovery) | STM32F429I-Discovery BSP Driver
[stm32f401-discovery](https://github.com/STMicroelectronics/stm32f401-discovery) | STM32F401-Discovery BSP Driver
[stm32446e-eval](https://github.com/STMicroelectronics/stm32446e-eval) | STM32446E_EVAL BSP Driver
[stm32f411e-discovery](https://github.com/STMicroelectronics/stm32f411e-discovery) | STM32F411E-Discovery BSP Driver
[stm32412g-discovery](https://github.com/STMicroelectronics/stm32412g-discovery) | STM32412G-Discovery BSP Driver
[stm32f413h-discovery](https://github.com/STMicroelectronics/stm32f413h-discovery) | STM32F413H-Discovery BSP Driver
[stm32f4-discovery](https://github.com/STMicroelectronics/stm32f4-discovery) | STM32F4-Discovery BSP Driver
[stm324x9i-eval](https://github.com/STMicroelectronics/stm324x9i-eval) | STM324x9I_EVAL BSP Driver

STM32CubeF7 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32756g-eval](https://github.com/STMicroelectronics/stm32756g-eval) | STM32756G_EVAL BSP Driver
[stm32f7308-dk](https://github.com/STMicroelectronics/stm32f7308-dk) | STM32F7308-Discovery BSP Driver
[stm32f7508-dk](https://github.com/STMicroelectronics/stm32f7508-dk) | STM32F7508-Discovery BSP Driver
[stm32f769i-eval](https://github.com/STMicroelectronics/stm32f769i-eval) | STM32F769I_EVAL BSP Driver
[stm32f7xx-nucleo-144](https://github.com/STMicroelectronics/stm32f7xx-nucleo-144) | F7 nucleo BSP Driver
[32f769idiscovery](https://github.com/STMicroelectronics/32f769idiscovery) | 32F769IDISCOVERY BSP Driver
[32f723ediscovery](https://github.com/STMicroelectronics/32f723ediscovery) | 32F723EDISCOVERY BSP Driver
[32f746gdiscovery](https://github.com/STMicroelectronics/32f746gdiscovery) | 32F746GDISCOVERY BSP Driver

STM32CubeG0 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32g0316-disco](https://github.com/STMicroelectronics/stm32g0316-disco) | STM32G0316-DISCO BSP Driver
[stm32g071b-disco](https://github.com/STMicroelectronics/stm32g071b-disco) | STM32G071B-DISCO BSP Driver
[stm32g081b-eval](https://github.com/STMicroelectronics/stm32g081b-eval) | STM32G081B_EVAL BSP Driver
[stm32g0c1e-ev](https://github.com/STMicroelectronics/stm32g0c1e-ev) | STM32G0C1E-EV BSP Driver
[stm32g0xx-nucleo](https://github.com/STMicroelectronics/stm32g0xx-nucleo) | G0 nucleo BSP Driver
[stm32g0xx-nucleo-32](https://github.com/STMicroelectronics/stm32g0xx-nucleo-32) | G0 nucleo BSP Driver

STM32CubeG4 BSP Boards Drivers | Description
-------------------------------|-------------
[b-g474e-dpow1](https://github.com/STMicroelectronics/b-g474e-dpow1) | B-G474E-DPOW1 BSP Driver
[stm32g474e-eval](https://github.com/STMicroelectronics/stm32g474e-eval) | STM32G474E-EVAL BSP Driver
[stm32g4xx-nucleo](https://github.com/STMicroelectronics/stm32g4xx-nucleo) | G4 nucleo BSP Driver

STM32CubeH7 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32h7b3i-dk](https://github.com/STMicroelectronics/stm32h7b3i-dk) | STM32H7B3I-DK BSP Driver
[stm32h750b-dk](https://github.com/STMicroelectronics/stm32h750b-dk) | STM32H750B-DK BSP Driver
[stm32h747i-eval](https://github.com/STMicroelectronics/stm32h747i-eval) | STM32H747I-EVAL BSP Driver
[stm32h747i-disco](https://github.com/STMicroelectronics/stm32h747i-disco) | STM32H747I-DISCO BSP Driver
[stm32h745i-disco](https://github.com/STMicroelectronics/stm32h745i-disco) | STM32H745I-DISCO BSP Driver
[stm32h743i-eval](https://github.com/STMicroelectronics/stm32h743i-eval) | STM32H743I-EVAL BSP Driver
[stm32h735g-dk](https://github.com/STMicroelectronics/stm32h735g-dk) | STM32H735G-DK BSP Driver
[stm32h7b3i-eval](https://github.com/STMicroelectronics/stm32h7b3i-eval) | STM32H7B3I-EVAL BSP Driver
[stm32h7xx-nucleo](https://github.com/STMicroelectronics/stm32h7xx-nucleo) | H7 nucleo BSP Driver

STM32CubeL0 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32l073z-eval](https://github.com/STMicroelectronics/stm32l073z-eval) | STM32L073Z-EVAL BSP Driver
[stm32l0xx-nucleo](https://github.com/STMicroelectronics/stm32l0xx-nucleo) | L0 nucleo BSP Driver
[stm32l0xx-nucleo-32](https://github.com/STMicroelectronics/stm32l0xx-nucleo-32) | L0 nucleo 32 BSP Driver
[32l0538discovery](https://github.com/STMicroelectronics/32l0538discovery) | 32L100CDISCOVERY BSP Driver

STM32CubeL1 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32l152d-eval](https://github.com/STMicroelectronics/stm32l152d-eval) | STM32L152D-EVAL BSP Driver
[stm32l1xx-nucleo](https://github.com/STMicroelectronics/stm32l1xx-nucleo) | L1 nucleo BSP Driver
[32l152cdiscovery](https://github.com/STMicroelectronics/32l152cdiscovery) | 32L152CDISCOVERY BSP Driver
[32l100cdiscovery](https://github.com/STMicroelectronics/32l100cdiscovery) | 32L100CDISCOVERY BSP Driver

STM32CubeL4 BSP Boards Drivers | Description
-------------------------------|-------------
[b-l475e-iot01a](https://github.com/STMicroelectronics/b-l475e-iot01a) | B-L475E-IOT01A BSP Driver
[b-l4s5i-iot01a](https://github.com/STMicroelectronics/b-l4s5i-iot01a) | B-L4S5I-IOT01A BSP Driver
[stm32l476g-eval](https://github.com/STMicroelectronics/stm32l476g-eval) | STM32L476G-EVAL BSP Driver
[stm32l4p5g-dk](https://github.com/STMicroelectronics/stm32l4p5g-dk) | STM32L4P5G-DK BSP Driver
[stm32l4r9i-eval](https://github.com/STMicroelectronics/stm32l4r9i-eval) | STM32L4R9I-EVAL BSP Driver
[stm32l4xx-nucleo](https://github.com/STMicroelectronics/stm32l4xx-nucleo) | L4 nucleo BSP Driver
[stm32l4xx-nucleo-144](https://github.com/STMicroelectronics/stm32l4xx-nucleo-144) | L4 nucleo 144 BSP Driver
[stm32l4xx-nucleo-32](https://github.com/STMicroelectronics/stm32l4xx-nucleo-32) | L4 nucleo 32 BSP Driver
[32l496gdiscovery](https://github.com/STMicroelectronics/32l496gdiscovery) | 32L496GDISCOVERY BSP Driver
[32l4r9idiscovery](https://github.com/STMicroelectronics/32l4r9idiscovery) | 32L4R9IDISCOVERY BSP Driver
[32l476gdiscovery](https://github.com/STMicroelectronics/32l476gdiscovery) | 32L476GDISCOVERY BSP Driver

STM32CubeL5 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32l562e-dk](https://github.com/STMicroelectronics/stm32l562e-dk) | STM32L562E-DK BSP Driver
[stm32l552e-ev](https://github.com/STMicroelectronics/stm32l552e-ev) | STM32L552E-EV BSP Driver
[stm32l5xx-nucleo](https://github.com/STMicroelectronics/stm32l5xx-nucleo) | L5 nucleo BSP Driver

STM32CubeU5 BSP Boards Drivers | Description
-------------------------------|-------------
[stm32u5xx-nucleo](https://github.com/STMicroelectronics/stm32u5xx-nucleo) | U5 nucleo BSP Driver

STM32CubeWB BSP Boards Drivers | Description
-------------------------------|-------------
[stm32wb5mm-dk](https://github.com/STMicroelectronics/stm32wb5mm-dk) | STM32WB5MM-DK BSP Driver
[nucleo-wb15cc](https://github.com/STMicroelectronics/nucleo-wb15cc) | NUCLEO-WB15CC BSP Driver
[p-nucleo-wb55-nucleo](https://github.com/STMicroelectronics/p-nucleo-wb55-nucleo) | P-NUCLEO-WB55.Nucleo BSP Driver
[p-nucleo-wb55-usb-dongle](https://github.com/STMicroelectronics/p-nucleo-wb55-usb-dongle) | P-NUCLEO-WB55.USBDongle BSP Driver

STM32CubeWL BSP Boards Drivers | Description
-------------------------------|-------------
[stm32wlxx-nucleo](https://github.com/STMicroelectronics/stm32wlxx-nucleo) | WL nucleo BSP Driver

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
[stm32-w25q80ew](https://github.com/STMicroelectronics/stm32-w25q80ew)         | The W25Q80EW BSP Component Driver

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

#### STM32Cube Middleware Libraries

The **Middleware Libraries** MCU Components propose the following set of stacks common to all STM32xx series very useful to design number of middleware-based user applications.

These **Middleware Libraries** delivered in standalone mode, permit to get in advance, compared to the full FW Packages, the new features or updates. Please take a look to the Release Note to verify the compatibility information.

* **FatFS library:** A set of platform- and storage device-independent services allowing user application to access storage devices and manage files.

* **FreeRTOS library:** A set of platform-independent services implementing a real-time operating system kernel for embedded devices and providing methods for multiple threads or tasks, mutexes, semaphores and software timers.

* **LwIP library:** LwIP (Lightweight IP) is an open-source TCP/IP stack designed to reduce resource usage while still offering a full-scale TCP stack. Among other services, it also offers a network interface, buffers and a memory management section, and an operating system emulation layer.

* **USB Device library:** A set of services allowing the configuration and the control of the USB on STM32 MCUs in **device mode**. It is mainly based on the "Core" and the "Class" modules including the common and most used features and APIs.

* **USB Host library:** A set of services allowing the configuration and the control of the USB on STM32 MCUs in **host mode**. It is mainly based on the "Core" and the "Class" modules including the common and most used features and APIs.

The dynamic usage of Middleware Libraries is provided thru projects examples, available in the respective STM32Cube MCU Packages **STM32Cubexx** where xx correspond to the series. Additionnal projects examples are also available under [stm32u5-classic-coremw-apps](https://github.com/STMicroelectronics/stm32u5-classic-coremw-apps).

STM32Cube MW Libraries | Description
---------------------- | -----------
[stm32_mw_fatfs](https://github.com/STMicroelectronics/stm32_mw_fatfs)           | FatFS middleware library
[stm32_mw_freertos](https://github.com/STMicroelectronics/stm32_mw_freertos)     | FreeRTOS middleware library
[stm32_mw_lwip](https://github.com/STMicroelectronics/stm32_mw_lwip)             | LwIP middleware library
[stm32_mw_usb_device](https://github.com/STMicroelectronics/stm32_mw_usb_device) | USB Device middleware library
[stm32_mw_usb_host](https://github.com/STMicroelectronics/stm32_mw_usb_host)     | USB Host middleware library

**Classic CoreMW** is a collection of applications for the above Middleware librairies.

Repository | Description
---------------------- | -----------
[stm32u5-classic-coremw-apps](https://github.com/STMicroelectronics/stm32u5-classic-coremw-apps)  | Project examples on STM32U5 for ST USB Device, ST USB Host, FreeRTOS, FatFS, and LwIP

### STM32Cube Utilities and Miscellaneous repos

Repository          | Description
------------------- | -----------
[stm32-external-loader](https://github.com/STMicroelectronics/stm32-external-loader) | Flashloaders source code of external memories embedded in the STM32 HW boards.
[stm32ai](https://github.com/STMicroelectronics/stm32ai)                             | Open source AI offer in STM32 products.
[STM32_open_pin_data](https://github.com/STMicroelectronics/STM32_open_pin_data)     | This repo provides all the information required for the pin and board configuration of products based on STM32 MCU.
