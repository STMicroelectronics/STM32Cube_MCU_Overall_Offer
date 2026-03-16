# STM32Cube HAL1-based Embedded Software

## Table of contents

* [STM32Cube MCU Packages](#stm32cube-mcu-packages)
* [STM32Cube Expansion Packages](#stm32cube-expansion-packages)
* [STM32Cube Function Packs](#stm32cube-function-packs)
* [STM32Cube CMSIS](#stm32cube-cmsis)
* [STM32Cube HAL Drivers](#stm32cube-hal-drivers)
* [STM32Cube BSP Drivers](#stm32cube-bsp-drivers)
* [STM32Cube MW Libraries and Applications](#stm32cube-middleware-libraries-and-applications)
* [STM32Cube USB-PD Components](#stm32cube-usb-power-delivery-components)
* [STM32Cube Utilities and miscellaneous](#stm32cube-utilities-and-miscellaneous-repos)

## STM32Cube MCU Packages

STM32Cube MCU Packages provide embedded software components, including drivers, middleware, and utilities, for developing applications on STM32 microcontrollers. Example projects demonstrate their use on STM32 boards. Additionally, the STM32Cube framework ensures portability across STM32 series.

MCU package | Repository
----------- | -----------
STM32CubeC0   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeC0)
STM32CubeF0   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeF0)
STM32CubeF1   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeF1)
STM32CubeF2   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeF2)
STM32CubeF3   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeF3)
STM32CubeF4   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeF4)
STM32CubeF7   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeF7)
STM32CubeH5   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeH5)
STM32CubeH7   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeH7)
STM32CubeH7RS | [Go to repository](https://github.com/STMicroelectronics/STM32CubeH7RS)
STM32CubeG0   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeG0)
STM32CubeG4   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeG4)
STM32CubeL0   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeL0)
STM32CubeL1   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeL1)
STM32CubeL4   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeL4)
STM32CubeL5   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeL5)
STM32CubeN6   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeN6)
STM32CubeU0   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeU0)
STM32CubeU3   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeU3)
STM32CubeU5   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeU5)
STM32CubeWB   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeWB)
STM32CubeWB0  | [Go to repository](https://github.com/STMicroelectronics/STM32CubeWB0)
STM32CubeWBA  | [Go to repository](https://github.com/STMicroelectronics/STM32CubeWBA)
STM32CubeWL   | [Go to repository](https://github.com/STMicroelectronics/STM32CubeWL)
STM32CubeWL3  | [Go to repository](https://github.com/STMicroelectronics/STM32CubeWL3)

## STM32Cube Expansion Packages

STM32Cube Expansion Packages complement the STM32Cube MCU Packages with additional software bricks, including specific drivers for external companion chips or application-specific middleware. They offer simplified implementations of real-world use cases in areas, such as sensing, power management, connectivity, and audio.

### Section content

- [STM32Cube AI X-CUBE](#stm32cube-ai-x-cube)
- [STM32Cube Azure RTOS X-CUBE](#stm32cube-azure-rtos-x-cube)
- [STM32Cube Connectivity X-CUBE](#stm32cube-connectivity-x-cube)
- [STM32Cube FreeRTOS X-CUBE](#stm32cube-freertos-x-cube)
- [STM32Cube IoT X-CUBE](#stm32cube-iot-x-cube)
- [STM32Cube MEMS and Sensors X-CUBE](#stm32cube-mems-and-sensors-x-cube)
- [STM32Cube USB-PD X-CUBE](#stm32cube-usb-pd-x-cube)
- [STM32Cube Miscellaneous X-CUBE](#stm32cube-miscellaneous-x-cube)

### STM32Cube AI X-CUBE

Expansion Package | Repository
----------------- | ----------
x-cube-image-processing                               | [Go to repository](https://github.com/STMicroelectronics/x-cube-image-processing)
x-cube-n6-ai-face-landmarks                           | [Go to repository](https://github.com/STMicroelectronics/x-cube-n6-ai-face-landmarks)
x-cube-n6-ai-h264-usb-uvc                             | [Go to repository](https://github.com/STMicroelectronics/x-cube-n6-ai-h264-usb-uvc)
x-cube-n6-ai-hand-landmarks                           | [Go to repository](https://github.com/STMicroelectronics/x-cube-n6-ai-hand-landmarks)
x-cube-n6-ai-multi-pose-estimation                    | [Go to repository](https://github.com/STMicroelectronics/x-cube-n6-ai-multi-pose-estimation)
x-cube-n6-ai-people-detection-tracking                | [Go to repository](https://github.com/STMicroelectronics/x-cube-n6-ai-people-detection-tracking)
x-cube-n6-ai-power-measurement                        | [Go to repository](https://github.com/STMicroelectronics/x-cube-n6-ai-power-measurement)
x-cube-n6-camera-capture                              | [Go to repository](https://github.com/STMicroelectronics/x-cube-n6-camera-capture)

### STM32Cube Azure RTOS X-CUBE

Expansion Package | Repository
----------------- | ----------
x-cube-azrtos-f4     | [Go to repository](https://github.com/STMicroelectronics/x-cube-azrtos-f4)
x-cube-azrtos-f7     | [Go to repository](https://github.com/STMicroelectronics/x-cube-azrtos-f7)
x-cube-azrtos-g0     | [Go to repository](https://github.com/STMicroelectronics/x-cube-azrtos-g0)
x-cube-azrtos-g4     | [Go to repository](https://github.com/STMicroelectronics/x-cube-azrtos-g4)
x-cube-azrtos-h7     | [Go to repository](https://github.com/STMicroelectronics/x-cube-azrtos-h7)
x-cube-azrtos-h7rs   | [Go to repository](https://github.com/STMicroelectronics/x-cube-azrtos-h7rs)
x-cube-azrtos-l4     | [Go to repository](https://github.com/STMicroelectronics/x-cube-azrtos-l4)
x-cube-azrtos-l5     | [Go to repository](https://github.com/STMicroelectronics/x-cube-azrtos-l5)
x-cube-azrtos-wb     | [Go to repository](https://github.com/STMicroelectronics/x-cube-azrtos-wb)
x-cube-azrtos-wl     | [Go to repository](https://github.com/STMicroelectronics/x-cube-azrtos-wl)

### STM32Cube Connectivity X-CUBE

Expansion Package | Repository
----------------- | ----------
x-cube-ble1      | [Go to repository](https://github.com/STMicroelectronics/x-cube-ble1)
x-cube-ble2      | [Go to repository](https://github.com/STMicroelectronics/X-CUBE-BLE2)
x-cube-blemgr    | [Go to repository](https://github.com/STMicroelectronics/x-cube-blemgr)
x-cube-nfc4      | [Go to repository](https://github.com/STMicroelectronics/X-CUBE-NFC4)
x-cube-nfc7      | [Go to repository](https://github.com/STMicroelectronics/x-cube-nfc7)
x-cube-sfxs2lp1  | [Go to repository](https://github.com/STMicroelectronics/x-cube-sfxs2lp1)
x-cube-st67w61   | [Go to repository](https://github.com/STMicroelectronics/x-cube-st67w61)
x-cube-subg2     | [Go to repository](https://github.com/STMicroelectronics/x-cube-subg2)

### STM32Cube FreeRTOS X-CUBE

Expansion Package | Repository
----------------- | ----------
x-cube-freertos | [Go to repository](https://github.com/STMicroelectronics/x-cube-freertos)

### STM32Cube IoT X-CUBE

Expansion Package | Repository
----------------- | ----------
x-cube-aws              | [Go to repository](https://github.com/STMicroelectronics/x-cube-aws)
x-cube-azure-telematics | [Go to repository](https://github.com/STMicroelectronics/x-cube-azure-telematics)
x-cube-iota1            | [Go to repository](https://github.com/STMicroelectronics/X-CUBE-IOTA1)

### STM32Cube MEMS and Sensors X-CUBE

Expansion Package | Repository
----------------- | ----------
x-cube-ispu        | [Go to repository](https://github.com/STMicroelectronics/x-cube-ispu)
x-cube-mems1       | [Go to repository](https://github.com/STMicroelectronics/x-cube-mems1)
x-cube-memsmic1    | [Go to repository](https://github.com/STMicroelectronics/x-cube-memsmic1)
x-cube-soundter1   | [Go to repository](https://github.com/STMicroelectronics/x-cube-soundter1)
x-cube-tof1        | [Go to repository](https://github.com/STMicroelectronics/x-cube-tof1)

### STM32Cube USB-PD X-CUBE

Expansion Package | Repository
----------------- | ----------
x-cube-tcpp       | [Go to repository](https://github.com/STMicroelectronics/x-cube-tcpp)
x-cube-usb-pd     | [Go to repository](https://github.com/STMicroelectronics/x-cube-usb-pd)

### STM32Cube Miscellaneous X-CUBE

Expansion Package | Repository
----------------- | ----------
x-cube-eeprma1    | [Go to repository](https://github.com/STMicroelectronics/X-CUBE-EEPRMA1)
x-cube-gnss1      | [Go to repository](https://github.com/STMicroelectronics/x-cube-gnss1)

## STM32Cube Function Packs

STM32 Function Packs (FP) are a combination of low-level drivers, middleware libraries and sample applications assembled into a single software package. You can get the entire list of available Function Packs on st.com [here](https://www.st.com/en/ecosystems/stm32-ode-function-packs.html).

The below list represents the Function Packs available on github.com

Function Pack | Repository
------------- | ----------
fp-atr-ble1       | [Go to repository](https://github.com/STMicroelectronics/fp-atr-ble1)
fp-atr-sigfox1    | [Go to repository](https://github.com/STMicroelectronics/fp-atr-sigfox1)
fp-aud-aec1       | [Go to repository](https://github.com/STMicroelectronics/fp-aud-aec1)
fp-aud-smartmic1  | [Go to repository](https://github.com/STMicroelectronics/fp-aud-smartmic1)
fp-sns-allmems1   | [Go to repository](https://github.com/STMicroelectronics/fp-sns-allmems1)
fp-sns-datalog1   | [Go to repository](https://github.com/STMicroelectronics/fp-sns-datalog1)
fp-sns-datalog2   | [Go to repository](https://github.com/STMicroelectronics/fp-sns-datalog2)
fp-ind-datalogmc  | [Go to repository](https://github.com/STMicroelectronics/fp-ind-datalogmc)
fp-sns-flight1    | [Go to repository](https://github.com/STMicroelectronics/fp-sns-flight1)
fp-sns-motenv1    | [Go to repository](https://github.com/STMicroelectronics/FP-SNS-MOTENV1)
fp-sns-motenvwb1  | [Go to repository](https://github.com/STMicroelectronics/fp-sns-motenvwb1)
fp-sns-smartag2   | [Go to repository](https://github.com/STMicroelectronics/fp-sns-smartag2)
fp-sns-stbox1     | [Go to repository](https://github.com/STMicroelectronics/fp-sns-stbox1)

## STM32Cube MCU Components

As mentioned above, the STM32Cube MCU Components are an **alternative** delivery model to the MCU Firmware _monolithic_ offer. Each software component is delivered in a dedicated repository, allowing users to select and download only those relevant to their application needs.

> [!NOTE]
> Care must be taken regarding the **cross-compatibility** of components. Please refer to the README.md file in each repository for details.

### STM32Cube CMSIS

The **CMSIS** interfaces offer access to the Arm Cortex®-M processor core features and device-specific peripherals of STM32 microcontrollers.

#### STM32Cube CMSIS Core

CMSIS Core      | Repository
--------------- | ----------
cmsis-core      | [Go to repository](https://github.com/STMicroelectronics/cmsis-core)

#### STM32Cube CMSIS Device

CMSIS Device         | Repository
-------------------- | ----------
cmsis-device-c0      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-c0)
cmsis-device-f0      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-f0)
cmsis-device-f1      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-f1)
cmsis-device-f2      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-f2)
cmsis-device-f3      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-f3)
cmsis-device-f4      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-f4)
cmsis-device-f7      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-f7)
cmsis-device-g0      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-g0)
cmsis-device-g4      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-g4)
cmsis-device-h5      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-h5)
cmsis-device-h7      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-h7)
cmsis-device-h7rs    | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-h7rs)
cmsis-device-l0      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-l0)
cmsis-device-l1      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-l1)
cmsis-device-l4      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-l4)
cmsis-device-l5      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-l5)
cmsis-device-n6      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-n6)
cmsis-device-u0      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-u0)
cmsis-device-u3      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-u3)
cmsis-device-u5      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-u5)
cmsis-device-wb      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-wb)
cmsis-device-wb0     | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-wb0)
cmsis-device-wba     | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-wba)
cmsis-device-wl      | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-wl)
cmsis-device-wl3     | [Go to repository](https://github.com/STMicroelectronics/cmsis-device-wl3)

### STM32Cube HAL Drivers

The **HAL Drivers** MCU Components propose the HAL and LL Drivers modules controlling all the hardware peripherals embedded in the STM32 products.

* HAL Drivers:
  * A set of portable abstraction APIs offering high level services, built around standalone processes. The HAL drivers are functionalities oriented, example: for the Timer peripheral, the APIs could be split into several categories following the functions offered by the IPs (Basic timer, capture, PWM...) for a communication IP: an initialisation function, eventually a configuration function and data transfer services (polling, interruption or DMA based)
  * The compatibility SHALL be guaranteed across all the STM32 families for the generic APIs, including generic macros and common structures defines. Any specific feature is given in a dedicated extension model available in the associated extension files
* LL Drivers:
  * Low Layer Drivers: a set of basic functions with direct hardware access (no standalone process), this layer can be called either by applications or by the HAL drivers.

Both HAL and LL drivers of each series are provided in the **same** repository. Their usage is illustrated thru **examples**, available in the respective STM32Cube MCU **Firmware** repositories.

HAL Driver                | Repository
------------------------- | ----------
stm32c0xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32c0xx-hal-driver)
stm32f0xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32f0xx-hal-driver)
stm32f1xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32f1xx-hal-driver)
stm32f2xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32f2xx-hal-driver)
stm32f3xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32f3xx-hal-driver)
stm32f4xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32f4xx-hal-driver)
stm32f7xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32f7xx-hal-driver)
stm32g0xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32g0xx-hal-driver)
stm32g4xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32g4xx-hal-driver)
stm32h5xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32h5xx-hal-driver)
stm32h7xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32h7xx-hal-driver)
stm32h7rsxx-hal-driver    | [Go to repository](https://github.com/STMicroelectronics/stm32h7rsxx-hal-driver)
stm32l0xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32l0xx-hal-driver)
stm32l1xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32l1xx-hal-driver)
stm32l4xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32l4xx-hal-driver)
stm32l5xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32l5xx-hal-driver)
stm32n6xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32n6xx-hal-driver)
stm32u0xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32u0xx-hal-driver)
stm32u3xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32u3xx-hal-driver)
stm32u5xx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32u5xx-hal-driver)
stm32wbxx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32wbxx-hal-driver)
stm32wb0x-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32wb0x-hal-driver)
stm32wbaxx-hal-driver     | [Go to repository](https://github.com/STMicroelectronics/stm32wbaxx-hal-driver)
stm32wlxx-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32wlxx-hal-driver)
stm32wl3x-hal-driver      | [Go to repository](https://github.com/STMicroelectronics/stm32wl3x-hal-driver)

### STM32Cube BSP Drivers

The **BSP Drivers** MCU Components propose the _Board Support Package_ Drivers, which are constituted from the:

* [STM32Cube BSP Board Drivers](#stm32cube-bsp-board-drivers), **based on the HAL drivers**, and providing a set of high level APIs allowing a quick access to the board services (**e.g.**, audio, graphics, access to external memories).
* [STM32Cube BSP Component Drivers](#stm32cube-bsp-component-drivers) providing a set of high level APIs allowing a quick access to harware components available on the board but external to the MCU (**e.g.**, audio codecs, LCD drivers, SD cards, MEMS). The **link** between these external components and the HAL drivers (**e.g.**, an SD card and the `OSPI`/`QSPI` HAL driver) is established within the **BSP Board** drivers.

------

**NOTE:** A number of BSP **component** drivers (particularly of MEMS) come in **two forms**, each addressing a different purpose. For each one of such BSP component drivers, **two repositories** are available as explained below:

* **PID:** Platform-Independent Drivers. Recognizable to their repositories' names *\<bspcomp\>* (**e.g.**, [hts221](https://github.com/STMicroelectronics/hts221)). Are **low-level** drivers allowing direct access to components' registers. These drivers are independent of any software platform, as the acronym PID suggests. The complete list can be found [here](https://github.com/STMicroelectronics/STMems_Standard_C_drivers).
* **STM32:** STM32Cube-compatible drivers. Recognizable to their repositories' names *stm32-\<bspcomp\>* (**e.g.**, [stm32-hts221](https://github.com/STMicroelectronics/stm32-hts221)). Are **hardware-abstracted** drivers, specially designed to be compatible with the STM32Cube software offer, as the `stm32-` prefix suggests. The complete list is provided [below](#stm32cube-bsp-component-drivers) (refer particularly to tables `MEMS` and `Temperature Sensor`).

------

### STM32Cube BSP Board Drivers

#### Section content

- [STM32CubeC0 BSP Boards Drivers](#stm32cubec0-bsp-boards-drivers)
- [STM32CubeF0 BSP Boards Drivers](#stm32cubef0-bsp-boards-drivers)
- [STM32CubeF1 BSP Boards Drivers](#stm32cubef1-bsp-boards-drivers)
- [STM32CubeF2 BSP Boards Drivers](#stm32cubef2-bsp-boards-drivers)
- [STM32CubeF3 BSP Boards Drivers](#stm32cubef3-bsp-boards-drivers)
- [STM32CubeF4 BSP Boards Drivers](#stm32cubef4-bsp-boards-drivers)
- [STM32CubeF7 BSP Boards Drivers](#stm32cubef7-bsp-boards-drivers)
- [STM32CubeG0 BSP Boards Drivers](#stm32cubeg0-bsp-boards-drivers)
- [STM32CubeG4 BSP Boards Drivers](#stm32cubeg4-bsp-boards-drivers)
- [STM32CubeH5 BSP Boards Drivers](#stm32cubeh5-bsp-boards-drivers)
- [STM32CubeH7RS BSP Boards Drivers](#stm32cubeh7rs-bsp-boards-drivers)
- [STM32CubeH7 BSP Boards Drivers](#stm32cubeh7-bsp-boards-drivers)
- [STM32CubeL0 BSP Boards Drivers](#stm32cubel0-bsp-boards-drivers)
- [STM32CubeL1 BSP Boards Drivers](#stm32cubel1-bsp-boards-drivers)
- [STM32CubeL4 BSP Boards Drivers](#stm32cubel4-bsp-boards-drivers)
- [STM32CubeL5 BSP Boards Drivers](#stm32cubel5-bsp-boards-drivers)
- [STM32CubeN6 BSP Boards Drivers](#stm32cuben6-bsp-boards-drivers)
- [STM32CubeU0 BSP Boards Drivers](#stm32cubeu0-bsp-boards-drivers)
- [STM32CubeU3 BSP Boards Drivers](#stm32cubeu3-bsp-boards-drivers)
- [STM32CubeU5 BSP Boards Drivers](#stm32cubeu5-bsp-boards-drivers)
- [STM32CubeWB BSP Boards Drivers](#stm32cubewb-bsp-boards-drivers)
- [STM32CubeWB0 BSP Boards Drivers](#stm32cubewb0-bsp-boards-drivers)
- [STM32CubeWBA BSP Boards Drivers](#stm32cubewba-bsp-boards-drivers)
- [STM32CubeWL BSP Boards Drivers](#stm32cubewl-bsp-boards-drivers)
- [STM32CubeWL3 BSP Boards Drivers](#stm32cubewl3-bsp-boards-drivers)

#### STM32CubeC0 BSP Boards Drivers

BSP Board Driver         | Repository
------------------------ | ----------
stm32c0xx-nucleo-bsp     | [Go to repository](https://github.com/STMicroelectronics/stm32c0xx-nucleo-bsp)
stm32c0116-dk-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32c0116-dk-bsp)
stm32c0316-dk-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32c0316-dk-bsp)

#### STM32CubeF0 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm32f0xx-nucleo-32-bsp     | [Go to repository](https://github.com/STMicroelectronics/stm32f0xx-nucleo-32-bsp)
stm32f0xx-nucleo-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32f0xx-nucleo-bsp)
stm32091c-eval-bsp          | [Go to repository](https://github.com/STMicroelectronics/stm32091c-eval-bsp)
stm32072b-eval-bsp          | [Go to repository](https://github.com/STMicroelectronics/stm32072b-eval-bsp)
32f072bdiscovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32f072bdiscovery-bsp)
32f0308discovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32f0308discovery-bsp)

#### STM32CubeF1 BSP Boards Drivers

BSP Board Driver        | Repository
----------------------- | ----------
stm3210c-eval-bsp       | [Go to repository](https://github.com/STMicroelectronics/stm3210c-eval-bsp)
stm3210e-eval-bsp       | [Go to repository](https://github.com/STMicroelectronics/stm3210e-eval-bsp)
stm32f1xx-nucleo-bsp    | [Go to repository](https://github.com/STMicroelectronics/stm32f1xx-nucleo-bsp)
stm32vldiscovery-bsp    | [Go to repository](https://github.com/STMicroelectronics/stm32vldiscovery-bsp)

#### STM32CubeF2 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm322xg-eval-bsp           | [Go to repository](https://github.com/STMicroelectronics/stm322xg-eval-bsp)
stm32f2xx-nucleo-144-bsp    | [Go to repository](https://github.com/STMicroelectronics/stm32f2xx-nucleo-144-bsp)

#### STM32CubeF3 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm32303c-eval-bsp          | [Go to repository](https://github.com/STMicroelectronics/stm32303c-eval-bsp)
stm32303e-eval-bsp          | [Go to repository](https://github.com/STMicroelectronics/stm32303e-eval-bsp)
stm32373c-eval-bsp          | [Go to repository](https://github.com/STMicroelectronics/stm32373c-eval-bsp)
stm32f3discovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32f3discovery-bsp)
stm32f3xx-nucleo-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32f3xx-nucleo-bsp)
stm32f3xx-nucleo-144-bsp    | [Go to repository](https://github.com/STMicroelectronics/stm32f3xx-nucleo-144-bsp)
stm32f3xx-nucleo-32-bsp     | [Go to repository](https://github.com/STMicroelectronics/stm32f3xx-nucleo-32-bsp)
32f3348discovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32f3348discovery-bsp)

#### STM32CubeF4 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm32f4xx-nucleo-144-bsp    | [Go to repository](https://github.com/STMicroelectronics/stm32f4xx-nucleo-144-bsp)
stm32f4xx-nucleo-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32f4xx-nucleo-bsp)
stm324xg-eval-bsp           | [Go to repository](https://github.com/STMicroelectronics/stm324xg-eval-bsp)
stm32469i-eval-bsp          | [Go to repository](https://github.com/STMicroelectronics/stm32469i-eval-bsp)
32f469idiscovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32f469idiscovery-bsp)
32f429idiscovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32f429idiscovery-bsp)
32f401cdiscovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32f401cdiscovery-bsp)
stm32446e-eval-bsp          | [Go to repository](https://github.com/STMicroelectronics/stm32446e-eval-bsp)
32f411ediscovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32f411ediscovery-bsp)
32f412gdiscovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32f412gdiscovery-bsp)
32f413hdiscovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32f413hdiscovery-bsp)
stm32f4discovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32f4discovery-bsp)
stm324x9i-eval-bsp          | [Go to repository](https://github.com/STMicroelectronics/stm324x9i-eval-bsp)

#### STM32CubeF7 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm32756g-eval-bsp          | [Go to repository](https://github.com/STMicroelectronics/stm32756g-eval-bsp)
stm32f7308-dk-bsp           | [Go to repository](https://github.com/STMicroelectronics/stm32f7308-dk-bsp)
stm32f7508-dk-bsp           | [Go to repository](https://github.com/STMicroelectronics/stm32f7508-dk-bsp)
stm32f769i-eval-bsp         | [Go to repository](https://github.com/STMicroelectronics/stm32f769i-eval-bsp)
stm32f7xx-nucleo-144-bsp    | [Go to repository](https://github.com/STMicroelectronics/stm32f7xx-nucleo-144-bsp)
32f769idiscovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32f769idiscovery-bsp)
32f723ediscovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32f723ediscovery-bsp)
32f746gdiscovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32f746gdiscovery-bsp)

#### STM32CubeG0 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm32g0316-disco-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32g0316-disco-bsp)
stm32g071b-disco-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32g071b-disco-bsp)
stm32g081b-eval-bsp         | [Go to repository](https://github.com/STMicroelectronics/stm32g081b-eval-bsp)
stm32g0c1e-ev-bsp           | [Go to repository](https://github.com/STMicroelectronics/stm32g0c1e-ev-bsp)
stm32g0xx-nucleo-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32g0xx-nucleo-bsp)
stm32g0xx-nucleo-32-bsp     | [Go to repository](https://github.com/STMicroelectronics/stm32g0xx-nucleo-32-bsp)

#### STM32CubeG4 BSP Boards Drivers

BSP Board Driver        | Repository
----------------------- | ----------
b-g474e-dpow1-bsp       | [Go to repository](https://github.com/STMicroelectronics/b-g474e-dpow1-bsp)
stm32g474e-eval-bsp     | [Go to repository](https://github.com/STMicroelectronics/stm32g474e-eval-bsp)
stm32g4xx-nucleo-bsp    | [Go to repository](https://github.com/STMicroelectronics/stm32g4xx-nucleo-bsp)

#### STM32CubeH5 BSP Boards Drivers

BSP Board Driver              | Repository
----------------------------- | ----------
stm32h573i-discovery-bsp      | [Go to repository](https://github.com/STMicroelectronics/stm32h573i-discovery-bsp)
stm32h5xx-nucleo-bsp          | [Go to repository](https://github.com/STMicroelectronics/stm32h5xx-nucleo-bsp)

#### STM32CubeH7RS BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm32h7s78-dk-bsp           | [Go to repository](https://github.com/STMicroelectronics/stm32h7s78-dk-bsp)
stm32h7rsxx-nucleo-bsp      | [Go to repository](https://github.com/STMicroelectronics/stm32h7rsxx-nucleo-bsp)

#### STM32CubeH7 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm32h7b3i-dk-bsp           | [Go to repository](https://github.com/STMicroelectronics/stm32h7b3i-dk-bsp)
stm32h750b-dk-bsp           | [Go to repository](https://github.com/STMicroelectronics/stm32h750b-dk-bsp)
stm32h747i-eval-bsp         | [Go to repository](https://github.com/STMicroelectronics/stm32h747i-eval-bsp)
stm32h747i-disco-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32h747i-disco-bsp)
stm32h745i-disco-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32h745i-disco-bsp)
stm32h743i-eval-bsp         | [Go to repository](https://github.com/STMicroelectronics/stm32h743i-eval-bsp)
stm32h735g-dk-bsp           | [Go to repository](https://github.com/STMicroelectronics/stm32h735g-dk-bsp)
stm32h7b3i-eval-bsp         | [Go to repository](https://github.com/STMicroelectronics/stm32h7b3i-eval-bsp)
stm32h7xx-nucleo-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32h7xx-nucleo-bsp)

#### STM32CubeL0 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm32l073z-eval-bsp         | [Go to repository](https://github.com/STMicroelectronics/stm32l073z-eval-bsp)
stm32l0xx-nucleo-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32l0xx-nucleo-bsp)
stm32l0xx-nucleo-32-bsp     | [Go to repository](https://github.com/STMicroelectronics/stm32l0xx-nucleo-32-bsp)
32l0538discovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32l0538discovery-bsp)

#### STM32CubeL1 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm32l152d-eval-bsp         | [Go to repository](https://github.com/STMicroelectronics/stm32l152d-eval-bsp)
stm32l1xx-nucleo-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32l1xx-nucleo-bsp)
32l152cdiscovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32l152cdiscovery-bsp)
32l100cdiscovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32l100cdiscovery-bsp)

#### STM32CubeL4 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
b-l475e-iot01a-bsp          | [Go to repository](https://github.com/STMicroelectronics/b-l475e-iot01a-bsp)
b-l4s5i-iot01a-bsp          | [Go to repository](https://github.com/STMicroelectronics/b-l4s5i-iot01a-bsp)
stm32l476g-eval-bsp         | [Go to repository](https://github.com/STMicroelectronics/stm32l476g-eval-bsp)
stm32l4p5g-dk-bsp           | [Go to repository](https://github.com/STMicroelectronics/stm32l4p5g-dk-bsp)
stm32l4r9i-eval-bsp         | [Go to repository](https://github.com/STMicroelectronics/stm32l4r9i-eval-bsp)
stm32l4xx-nucleo-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32l4xx-nucleo-bsp)
stm32l4xx-nucleo-144-bsp    | [Go to repository](https://github.com/STMicroelectronics/stm32l4xx-nucleo-144-bsp)
stm32l4xx-nucleo-32-bsp     | [Go to repository](https://github.com/STMicroelectronics/stm32l4xx-nucleo-32-bsp)
32l496gdiscovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32l496gdiscovery-bsp)
32l4r9idiscovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32l4r9idiscovery-bsp)
32l476gdiscovery-bsp        | [Go to repository](https://github.com/STMicroelectronics/32l476gdiscovery-bsp)

#### STM32CubeL5 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm32l562e-dk-bsp           | [Go to repository](https://github.com/STMicroelectronics/stm32l562e-dk-bsp)
stm32l552e-ev-bsp           | [Go to repository](https://github.com/STMicroelectronics/stm32l552e-ev-bsp)
stm32l5xx-nucleo-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32l5xx-nucleo-bsp)

#### STM32CubeN6 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm32n6570-dk-bsp           | [Go to repository](https://github.com/STMicroelectronics/stm32n6570-dk-bsp)
stm32n6xx-nucleo-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32n6xx-nucleo-bsp)

#### STM32CubeU0 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm32u083c-dk-bsp           | [Go to repository](https://github.com/STMicroelectronics/stm32u083c-dk-bsp)
stm32u0xx-nucleo-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32u0xx-nucleo-bsp)

#### STM32CubeU3 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm32u3xx-nucleo-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32u3xx-nucleo-bsp)

#### STM32CubeU5 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
b-u585i-iot02a-bsp          | [Go to repository](https://github.com/STMicroelectronics/b-u585i-iot02a-bsp)
stm32u575i-ev-bsp           | [Go to repository](https://github.com/STMicroelectronics/stm32u575i-ev-bsp)
stm32u5x9j-dk-bsp           | [Go to repository](https://github.com/STMicroelectronics/stm32u5x9j-dk-bsp)
stm32u5g9j-dk2-bsp          | [Go to repository](https://github.com/STMicroelectronics/stm32u5g9j-dk2-bsp)
stm32u5xx-nucleo-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32u5xx-nucleo-bsp)

#### STM32CubeWB BSP Boards Drivers

BSP Board Driver                  | Repository
--------------------------------- | ----------
stm32wb5mm-dk-bsp                 | [Go to repository](https://github.com/STMicroelectronics/stm32wb5mm-dk-bsp)
nucleo-wb15cc-bsp                 | [Go to repository](https://github.com/STMicroelectronics/nucleo-wb15cc-bsp)
p-nucleo-wb55-nucleo-bsp          | [Go to repository](https://github.com/STMicroelectronics/p-nucleo-wb55-nucleo-bsp)
p-nucleo-wb55-usb-dongle-bsp      | [Go to repository](https://github.com/STMicroelectronics/p-nucleo-wb55-usb-dongle-bsp)
b-wb1m-wpan1-bsp                  | [Go to repository](https://github.com/STMicroelectronics/b-wb1m-wpan1-bsp)

#### STM32CubeWB0 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm32wb0x-nucleo-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32wb0x-nucleo-bsp)

#### STM32CubeWBA BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
b-wba5m-wpan-bsp            | [Go to repository](https://github.com/STMicroelectronics/b-wba5m-wpan-bsp)
b-wba6m-wpan-bsp            | [Go to repository](https://github.com/STMicroelectronics/b-wba6m-wpan-bsp)
stm32wbaxx-nucleo-bsp       | [Go to repository](https://github.com/STMicroelectronics/stm32wbaxx-nucleo-bsp)
stm32wba55g-dk1-bsp         | [Go to repository](https://github.com/STMicroelectronics/stm32wba55g-dk1-bsp)
stm32wba65ri-dk1-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32wba65ri-dk1-bsp)

#### STM32CubeWL BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm32wlxx-nucleo-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32wlxx-nucleo-bsp)
b-wl5m-subg1-bsp            | [Go to repository](https://github.com/STMicroelectronics/b-wl5m-subg1-bsp)

#### STM32CubeWL3 BSP Boards Drivers

BSP Board Driver            | Repository
--------------------------- | ----------
stm32wl3x-nucleo-bsp        | [Go to repository](https://github.com/STMicroelectronics/stm32wl3x-nucleo-bsp)

### STM32Cube BSP Component Drivers

#### Section content

- [STM32Cube BSP Audio Component Drivers](#stm32cube-bsp-audio-component-drivers)
- [STM32Cube BSP BLE Component Drivers](#stm32cube-bsp-ble-component-drivers)
- [STM32Cube BSP Camera Component Drivers](#stm32cube-bsp-camera-component-drivers)
- [STM32Cube BSP Display Component Drivers](#stm32cube-bsp-display-component-drivers)
- [STM32Cube BSP EEPROM Component Drivers](#stm32cube-bsp-eeprom-component-drivers)
- [STM32Cube BSP E-Paper Display Component Drivers](#stm32cube-bsp-e-paper-display-component-drivers)
- [STM32Cube BSP IO Expander Component Drivers](#stm32cube-bsp-io-expander-component-drivers)
- [STM32Cube BSP LCD Component Drivers](#stm32cube-bsp-lcd-component-drivers)
- [STM32Cube BSP MEMS Component Drivers](#stm32cube-bsp-mems-component-drivers)
- [STM32Cube BSP Networking Component Drivers](#stm32cube-bsp-networking-component-drivers)
- [STM32Cube BSP NFC/RFID Tag Component Drivers](#stm32cube-bsp-nfcrfid-tag-component-drivers)
- [STM32Cube BSP Power Monitoring Component Drivers](#stm32cube-bsp-power-monitoring-component-drivers)
- [STM32Cube BSP xSPI-Interfaced Memory Component Drivers](#stm32cube-bsp-xspi-interfaced-memory-component-drivers)
- [STM32Cube BSP SDRAM Component Drivers](#stm32cube-bsp-sdram-component-drivers)
- [STM32Cube BSP Temperature and Humidity Sensor Component Drivers](#stm32cube-bsp-temperature-and-humidity-sensor-component-drivers)
- [STM32Cube BSP Touch Screen Component Drivers](#stm32cube-bsp-touch-screen-component-drivers)
- [STM32Cube BSP USB-C Component Drivers](#stm32cube-bsp-usb-c-component-drivers)
- [STM32Cube BSP Wi-Fi Component Drivers](#stm32cube-bsp-wi-fi-component-drivers)
- [STM32Cube BSP Miscellaneous Sensor Component Drivers](#stm32cube-bsp-miscellaneous-sensor-component-drivers)

#### STM32Cube BSP Audio Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-adv7533      | [Go to repository](https://github.com/STMicroelectronics/stm32-adv7533)
stm32-ak4343       | [Go to repository](https://github.com/STMicroelectronics/stm32-ak4343)
stm32-cs42l51      | [Go to repository](https://github.com/STMicroelectronics/stm32-cs42l51)
stm32-cs42l52      | [Go to repository](https://github.com/STMicroelectronics/stm32-cs42l52)
stm32-cs43l22      | [Go to repository](https://github.com/STMicroelectronics/stm32-cs43l22)
stm32-wm8904       | [Go to repository](https://github.com/STMicroelectronics/stm32-wm8904)
stm32-wm8994       | [Go to repository](https://github.com/STMicroelectronics/stm32-wm8994)

#### STM32Cube BSP BLE Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-wb-at        | [Go to repository](https://github.com/STMicroelectronics/stm32-wb-at)

#### STM32Cube BSP Camera Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-imx335       | [Go to repository](https://github.com/STMicroelectronics/stm32-imx335)
stm32-ov2640       | [Go to repository](https://github.com/STMicroelectronics/stm32-ov2640)
stm32-ov5640       | [Go to repository](https://github.com/STMicroelectronics/stm32-ov5640)
stm32-ov9655       | [Go to repository](https://github.com/STMicroelectronics/stm32-ov9655)
stm32-s5k5cag      | [Go to repository](https://github.com/STMicroelectronics/stm32-s5k5cag)

#### STM32Cube BSP Display Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-sn65dp141    | [Go to repository](https://github.com/STMicroelectronics/stm32-sn65dp141)

#### STM32Cube BSP EEPROM Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-m24256       | [Go to repository](https://github.com/STMicroelectronics/stm32-m24256)
stm32-m95p32       | [Go to repository](https://github.com/STMicroelectronics/stm32-m95p32)

#### STM32Cube BSP E-Paper Display Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-gde021a1     | [Go to repository](https://github.com/STMicroelectronics/stm32-gde021a1)
stm32-gdem0213b74  | [Go to repository](https://github.com/STMicroelectronics/stm32-gdem0213b74)

#### STM32Cube BSP IO Expander Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-mfxstm32l152  | [Go to repository](https://github.com/STMicroelectronics/stm32-mfxstm32l152)
stm32-stmpe1600     | [Go to repository](https://github.com/STMicroelectronics/stm32-stmpe1600)
stm32-stmpe811      | [Go to repository](https://github.com/STMicroelectronics/stm32-stmpe811)

#### STM32Cube BSP LCD Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-ampire480272 | [Go to repository](https://github.com/STMicroelectronics/stm32-ampire480272)
stm32-ampire640480 | [Go to repository](https://github.com/STMicroelectronics/stm32-ampire640480)
stm32-hx8347d      | [Go to repository](https://github.com/STMicroelectronics/stm32-hx8347d)
stm32-hx8347g      | [Go to repository](https://github.com/STMicroelectronics/stm32-hx8347g)
stm32-hx8347i      | [Go to repository](https://github.com/STMicroelectronics/stm32-hx8347i)
stm32-ili9320      | [Go to repository](https://github.com/STMicroelectronics/stm32-ili9320)
stm32-ili9325      | [Go to repository](https://github.com/STMicroelectronics/stm32-ili9325)
stm32-ili9328      | [Go to repository](https://github.com/STMicroelectronics/stm32-ili9328)
stm32-ili9341      | [Go to repository](https://github.com/STMicroelectronics/stm32-ili9341)
stm32-ls016b8uy    | [Go to repository](https://github.com/STMicroelectronics/stm32-ls016b8uy)
stm32-nt35510      | [Go to repository](https://github.com/STMicroelectronics/stm32-nt35510)
stm32-otm8009a     | [Go to repository](https://github.com/STMicroelectronics/stm32-otm8009a)
stm32-rk043fn48h   | [Go to repository](https://github.com/STMicroelectronics/stm32-rk043fn48h)
stm32-rk050hr18    | [Go to repository](https://github.com/STMicroelectronics/stm32-rk050hr18)
stm32-rk070er9427  | [Go to repository](https://github.com/STMicroelectronics/stm32-rk070er9427)
stm32-spfd5408     | [Go to repository](https://github.com/STMicroelectronics/stm32-spfd5408)
stm32-ssd1315      | [Go to repository](https://github.com/STMicroelectronics/stm32-ssd1315)
stm32-st7735       | [Go to repository](https://github.com/STMicroelectronics/stm32-st7735)
stm32-st7789h2     | [Go to repository](https://github.com/STMicroelectronics/stm32-st7789h2)

#### STM32Cube BSP MEMS Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-hts221       | [Go to repository](https://github.com/STMicroelectronics/stm32-hts221)
stm32-iis2mdc      | [Go to repository](https://github.com/STMicroelectronics/stm32-iis2mdc)
stm32-ism330dhcx   | [Go to repository](https://github.com/STMicroelectronics/stm32-ism330dhcx)
stm32-ism330dlc    | [Go to repository](https://github.com/STMicroelectronics/stm32-ism330dlc)
stm32-i3g4250d     | [Go to repository](https://github.com/STMicroelectronics/stm32-i3g4250d)
stm32-l3gd20       | [Go to repository](https://github.com/STMicroelectronics/stm32-l3gd20)
stm32-lis302dl     | [Go to repository](https://github.com/STMicroelectronics/stm32-lis302dl)
stm32-lis3dsh      | [Go to repository](https://github.com/STMicroelectronics/stm32-lis3dsh)
stm32-lis3mdl      | [Go to repository](https://github.com/STMicroelectronics/stm32-lis3mdl)
stm32-lps22hb      | [Go to repository](https://github.com/STMicroelectronics/stm32-lps22hb)
stm32-lps22hh      | [Go to repository](https://github.com/STMicroelectronics/stm32-lps22hh)
stm32-lsm303agr    | [Go to repository](https://github.com/STMicroelectronics/stm32-lsm303agr)
stm32-lsm303c      | [Go to repository](https://github.com/STMicroelectronics/stm32-lsm303c)
stm32-lsm303dlhc   | [Go to repository](https://github.com/STMicroelectronics/stm32-lsm303dlhc)
stm32-lsm6dsl      | [Go to repository](https://github.com/STMicroelectronics/stm32-lsm6dsl)
stm32-s70kl1281    | [Go to repository](https://github.com/STMicroelectronics/stm32-s70kl1281)

#### STM32Cube BSP Networking Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-lan8742      | [Go to repository](https://github.com/STMicroelectronics/stm32-lan8742)
stm32-rtl8211      | [Go to repository](https://github.com/STMicroelectronics/stm32-rtl8211)

#### STM32Cube BSP NFC/RFID Tag Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-m24lr64      | [Go to repository](https://github.com/STMicroelectronics/stm32-m24lr64)
stm32-m24sr        | [Go to repository](https://github.com/STMicroelectronics/stm32-m24sr)
stm32-st25dv       | [Go to repository](https://github.com/STMicroelectronics/stm32-st25dv)

#### STM32Cube BSP Power Monitoring Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-ina230       | [Go to repository](https://github.com/STMicroelectronics/stm32-ina230)

#### STM32Cube BSP xSPI-Interfaced Memory Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-aps256         | [Go to repository](https://github.com/STMicroelectronics/stm32-aps256)
stm32-aps512         | [Go to repository](https://github.com/STMicroelectronics/stm32-aps512)
stm32-iss66wvh8m8    | [Go to repository](https://github.com/STMicroelectronics/stm32-iss66wvh8m8)
stm32-mt25ql512abb   | [Go to repository](https://github.com/STMicroelectronics/stm32-mt25ql512abb)
stm32-mt25tl01g      | [Go to repository](https://github.com/STMicroelectronics/stm32-mt25tl01g)
stm32-mx25l4006      | [Go to repository](https://github.com/STMicroelectronics/stm32-mx25l4006)
stm32-mx25l512       | [Go to repository](https://github.com/STMicroelectronics/stm32-mx25l512)
stm32-mx25lm51245g   | [Go to repository](https://github.com/STMicroelectronics/stm32-mx25lm51245g)
stm32-mx25r6435f     | [Go to repository](https://github.com/STMicroelectronics/stm32-mx25r6435f)
stm32-mx25um51245g   | [Go to repository](https://github.com/STMicroelectronics/stm32-mx25um51245g)
stm32-mx25uw25645g   | [Go to repository](https://github.com/STMicroelectronics/stm32-mx25uw25645g)
stm32-mx66uw1g45g    | [Go to repository](https://github.com/STMicroelectronics/stm32-mx66uw1g45g)
stm32-n25q128a       | [Go to repository](https://github.com/STMicroelectronics/stm32-n25q128a)
stm32-n25q256a       | [Go to repository](https://github.com/STMicroelectronics/stm32-n25q256a)
stm32-n25q512a       | [Go to repository](https://github.com/STMicroelectronics/stm32-n25q512a)
stm32-s25fl128s      | [Go to repository](https://github.com/STMicroelectronics/stm32-s25fl128s)
stm32-s25fl512s      | [Go to repository](https://github.com/STMicroelectronics/stm32-s25fl512s)
stm32-w25q128j       | [Go to repository](https://github.com/STMicroelectronics/stm32-w25q128j)

#### STM32Cube BSP SDRAM Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-is42s16800j    | [Go to repository](https://github.com/STMicroelectronics/stm32-is42s16800j)
stm32-is42s32800g    | [Go to repository](https://github.com/STMicroelectronics/stm32-is42s32800g)
stm32-is42s32800j    | [Go to repository](https://github.com/STMicroelectronics/stm32-is42s32800j)
stm32-mt48lc4m32b2   | [Go to repository](https://github.com/STMicroelectronics/stm32-mt48lc4m32b2)

#### STM32Cube BSP Temperature and Humidity Sensor Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-sht40ad1b    | [Go to repository](https://github.com/STMicroelectronics/stm32-sht40ad1b)
stm32-stlm75       | [Go to repository](https://github.com/STMicroelectronics/stm32-stlm75)
stm32-stts22h      | [Go to repository](https://github.com/STMicroelectronics/stm32-stts22h)
stm32-stts751      | [Go to repository](https://github.com/STMicroelectronics/stm32-stts751)

#### STM32Cube BSP Touch Screen Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-cy8c4014lqi  | [Go to repository](https://github.com/STMicroelectronics/stm32-cy8c4014lqi)
stm32-exc7200      | [Go to repository](https://github.com/STMicroelectronics/stm32-exc7200)
stm32-exc80w32     | [Go to repository](https://github.com/STMicroelectronics/stm32-exc80w32)
stm32-ft3x67       | [Go to repository](https://github.com/STMicroelectronics/stm32-ft3x67)
stm32-ft6x06       | [Go to repository](https://github.com/STMicroelectronics/stm32-ft6x06)
stm32-ft5336       | [Go to repository](https://github.com/STMicroelectronics/stm32-ft5336)
stm32-gt911        | [Go to repository](https://github.com/STMicroelectronics/stm32-gt911)
stm32-sitronix     | [Go to repository](https://github.com/STMicroelectronics/stm32-sitronix)
stm32-ts3510       | [Go to repository](https://github.com/STMicroelectronics/stm32-ts3510)

#### STM32Cube BSP USB-C Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-cbtl08gp053  | [Go to repository](https://github.com/STMicroelectronics/stm32-cbtl08gp053)
stm32-tusb546      | [Go to repository](https://github.com/STMicroelectronics/stm32-tusb546)

#### STM32Cube BSP Wi-Fi Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-es-wifi      | [Go to repository](https://github.com/STMicroelectronics/stm32-es-wifi)
stm32-mx-wifi      | [Go to repository](https://github.com/STMicroelectronics/stm32-mx-wifi)

#### STM32Cube BSP Miscellaneous Sensor Component Drivers

BSP Component Driver | Repository
-------------------- | ----------
stm32-ilps22qs     | [Go to repository](https://github.com/STMicroelectronics/stm32-ilps22qs)
stm32-veml3235     | [Go to repository](https://github.com/STMicroelectronics/stm32-veml3235)
stm32-veml6030     | [Go to repository](https://github.com/STMicroelectronics/stm32-veml6030)
stm32-vl53l5cx     | [Go to repository](https://github.com/STMicroelectronics/stm32-vl53l5cx)

### STM32Cube Middleware Libraries and Applications

Middleware libraries provide software modules that handle common functions like communication, file systems, real-time operating systems (RTOS), and graphics, simplifying application development across STM32 microcontrollers.

#### Section content

- [STM32Cube Classic Core MW Libraries](#stm32cube-classic-core-mw-libraries)
- [STM32Cube Azure RTOS MW Libraries](#stm32cube-azure-rtos-mw-libraries)
- [STM32Cube Miscellaneous MW Libraries](#stm32cube-miscellaneous-mw-libraries)
- [STM32Cube Classic Core MW Applications](#stm32cube-classic-core-mw-applications)
- [STM32Cube Eclipse Core MW Applications](#stm32cube-eclipse-core-mw-applications)
- [STM32Cube Open Bootloader MW Applications](#stm32cube-open-bootloader-mw-applications)

#### STM32Cube Classic Core MW Libraries

Middleware library  | Repository
------------------- | ----------
stm32-mw-fatfs      | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-fatfs)
stm32-mw-freertos   | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-freertos)
stm32-mw-lwip       | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-lwip)
stm32-mw-usb-device | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-usb-device)
stm32-mw-usb-host   | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-usb-host)

#### STM32Cube Azure RTOS MW Libraries

Middleware library      | Repository
----------------------- | ----------
stm32-mw-cmsis-rtos-tx  | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-cmsis-rtos-tx)
stm32-mw-filex          | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-filex)
stm32-mw-levelx         | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-levelx)
stm32-mw-netxduo        | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-netxduo)
stm32-mw-threadx        | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-threadx)
stm32-mw-usbx           | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-usbx)

#### STM32Cube Miscellaneous MW Libraries

Middleware library      | Repository
----------------------- | ----------
stm32-mw-extmem-ldr     | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-extmem-ldr)
stm32-mw-extmem-mgr     | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-extmem-mgr)
stm32-mw-lorawan        | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-lorawan)
stm32-mw-mbedtls        | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-mbedtls)
stm32-mw-mcuboot        | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-mcuboot)
stm32-mw-openbl         | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-openbl)
stm32-mw-venc-ewl       | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-venc-ewl)

#### STM32Cube Classic Core MW Applications

Middleware application             | Repository
---------------------------------- | ----------
stm32c0-classic-coremw-apps        | [Go to repository](https://github.com/STMicroelectronics/stm32c0-classic-coremw-apps)
stm32h5-classic-coremw-apps        | [Go to repository](https://github.com/STMicroelectronics/stm32h5-classic-coremw-apps)
stm32n6-classic-coremw-apps        | [Go to repository](https://github.com/STMicroelectronics/stm32n6-classic-coremw-apps)
stm32u0-classic-coremw-apps        | [Go to repository](https://github.com/STMicroelectronics/stm32u0-classic-coremw-apps)
stm32u3-classic-coremw-apps        | [Go to repository](https://github.com/STMicroelectronics/stm32u3-classic-coremw-apps)
stm32u5-classic-coremw-apps        | [Go to repository](https://github.com/STMicroelectronics/stm32u5-classic-coremw-apps)
stm32wba-classic-coremw-apps       | [Go to repository](https://github.com/STMicroelectronics/stm32wba-classic-coremw-apps)

#### STM32Cube Eclipse Core MW Applications

Middleware application              | Repository
----------------------------------- | ----------
stm32n6-eclipse-coremw-apps         | [Go to repository](https://github.com/STMicroelectronics/stm32n6-eclipse-coremw-apps)
stm32h5-eclipse-coremw-apps         | [Go to repository](https://github.com/STMicroelectronics/stm32h5-eclipse-coremw-apps)
stm32u3-eclipse-coremw-apps         | [Go to repository](https://github.com/STMicroelectronics/stm32u3-eclipse-coremw-apps)
stm32wba-eclipse-coremw-apps        | [Go to repository](https://github.com/STMicroelectronics/stm32wba-eclipse-coremw-apps)

#### STM32Cube Open Bootloader MW Applications

Middleware application | Repository
---------------------- | ----------
stm32l5-openbl-apps   | [Go to repository](https://github.com/STMicroelectronics/stm32l5-openbl-apps)
stm32wb-openbl-apps   | [Go to repository](https://github.com/STMicroelectronics/stm32wb-openbl-apps)
stm32wl-openbl-apps   | [Go to repository](https://github.com/STMicroelectronics/stm32wl-openbl-apps)

### STM32Cube USB Power Delivery Components

The USB Power Delivery (USB-PD) software stack includes middleware, BSP drivers, and utilities such as debugging tools, providing a comprehensive solution for USB Power Delivery implementation.

#### Section content

- [STM32Cube USB-PD MW Libraries](#stm32cube-usb-pd-mw-libraries)
- [STM32Cube USB-PD BSP Component Drivers](#stm32cube-usb-pd-bsp-component-drivers)
- [STM32Cube USB-PD Utilities](#stm32cube-usb-pd-utilities)

#### STM32Cube USB-PD MW Libraries

Middleware library              | Repository
------------------------------- | ----------
stm32-mw-usbpd-core             | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-usbpd-core)
stm32-mw-usbpd-device-g0        | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-usbpd-device-g0)
stm32-mw-usbpd-device-g4        | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-usbpd-device-g4)
stm32-mw-usbpd-device-h5        | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-usbpd-device-h5)
stm32-mw-usbpd-device-h7rs      | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-usbpd-device-h7rs)
stm32-mw-usbpd-device-l5        | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-usbpd-device-l5)
stm32-mw-usbpd-device-u5        | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-usbpd-device-u5)
stm32-mw-usbpd-ucsi             | [Go to repository](https://github.com/STMicroelectronics/stm32-mw-usbpd-ucsi)

#### STM32Cube USB-PD BSP Component Drivers

BSP component driver            | Repository
------------------------------- | ----------
stm32-bsp-usbpd-tcpp0203        | [Go to repository](https://github.com/STMicroelectronics/stm32-bsp-usbpd-tcpp0203)

#### STM32Cube USB-PD Utilities

Utility                         | Repository
------------------------------- | ----------
stm32-util-usbpd-tracer-emb     | [Go to repository](https://github.com/STMicroelectronics/stm32-util-usbpd-tracer-emb)

### STM32Cube Utilities and Miscellaneous repos

These repositories provide tools and resources to assist development with STM32 microcontrollers.

Utility and miscellaneous   | Repository
--------------------------- | ----------
stm32-external-loader       | [Go to repository](https://github.com/STMicroelectronics/stm32-external-loader)
stm32ai                     | [Go to repository](https://github.com/STMicroelectronics/stm32ai)
STM32_open_pin_data         | [Go to repository](https://github.com/STMicroelectronics/STM32_open_pin_data)
