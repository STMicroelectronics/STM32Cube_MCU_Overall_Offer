![banner](./images/stm32cube_github_banner.png)

# STM32Cube Embedded Software

## Offer overview

STM32Cube empowers developers to achieve **design success** by providing a comprehensive suite of professional development tools and embedded software components. This ecosystem helps you **differentiate** your product, **accelerate** design cycles, and **reduce** costs.

This repository offers a concise overview of the **STM32Cube embedded software** available for [STM32 microcontrollers](https://www.st.com/en/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus.html), along with links to the relevant repositories.

> [!NOTE]
> A separate repository, [STM32MPU_EmbSW_Overall_Offer](https://github.com/STMicroelectronics/STM32MPU_EmbSW_Overall_Offer/blob/master/README.md), covers the STM32 MPU offer on GitHub.

For a broader understanding of the STM32Cube ecosystem and its tools, please refer to [Getting Started with STM32Cube Ecosystem](https://dev.st.com/stm32cube-docs/stm32cube-getting-started).

On STMicroelectronics’ GitHub organization, you will find repositories covering most of the **STM32Cube Embedded Software**. These resources are also accessible via www.st.com, the **STM32CubeMX** tool, and the **STM32 Example Library**.

Beyond the all-in-one repositories, which include example projects for popular STM32 Development Kits like **Nucleo** and **Discovery** promotion boards, the platform provides **modular** repositories for specific components and packs, such as:
* The **CMSIS** interfaces, offering access to the Arm Cortex®-M processor core features and device-specific peripherals of STM32 microcontrollers,
* The STM32Cube **Hardware Abstraction Layer (HAL)** ensuring maximum **portability** across the STM32 portfolio, complemented by the **low-layer (LL)** APIs — a **lightweight**, expert-oriented layer closer to the hardware. Both HAL and LL APIs can be used **together** with minimal restrictions,
* Drivers for **additional hardware** found on the promotion boards (**e.g.,** external memories, audio codecs, screen controllers),
* **Middleware** including RTOS, USB, file systems, touch sensing, and open bootloader,
* **Utilities** including standard output redirection and basic task scheduling for bare-metal applications.

These repositories also empower STM32 developers to **report issues** and **contribute updates**, facilitated by a *Contributor License Agreement* feature (see each repository’s CONTRIBUTING guide).

> [!NOTE]
> For broader support or non-software-related inquiries, please visit the [ST Community](https://community.st.com/s/topiccatalog) or [ST Support Center](https://my.st.com/ols#/ols/).

The STM32Cube Hardware Abstraction Layer (HAL) is available in two major versions.
* The first one, **HAL1** (version `1.x.x`), is included in the STM32Cube MCU packages listed [here](#hal1-based-software), but also in the STM32Cube MPU packages.
* The second one, **HAL2** (version `2.x.x`), is included in the STM32Cube MCU packages listed [here](#hal2-based-software). It is introduced with the latest STM32 series and offers enhanced features and improved performance.

Depending on your STM32 series, we recommend starting with the appropriate introduction page as outlined in the tables below.

### HAL2-based software

STM32 MCUs          | STM32 series
--------------------|--------------
Mainstream       <img src="./images/icon_mainstream.png"      alt="Mainstream"       width="25"/> | [STM32C5](./STM32Cube_STM32C5.md)

### [HAL1-based software](./STM32Cube_HAL1_Offer.md)

STM32 MCUs          | STM32 series
--------------------|--------------
Mainstream       <img src="./images/icon_mainstream.png"      alt="Mainstream"       width="25"/> | STM32C0, STM32F0, STM32F1, STM32F3, STM32G0, STM32G4
High-performance <img src="./images/icon_high_perf.png"       alt="High-performance" width="25"/> | STM32F2, STM32F4, STM32F7, STM32H5, STM32H7, STM32H7RS, STM32N6
Ultra-low-power  <img src="./images/icon_ultra_low_power.png" alt="Ultra-low-power"  width="25"/> | STM32L0, STM32L1, STM32L4, STM32L5, STM32U0, STM32U3, STM32U5
Wireless         <img src="./images/icon_wireless.png"        alt="Wireless"         width="25"/> | STM32WB, STM32WB0, STM32WBA, STM32WL, STM32WL3
