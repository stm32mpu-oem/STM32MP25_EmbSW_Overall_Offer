## STM32MP25_EmbSW_Overall_Offer Overview

STM32MPU Embedded Software distribution is a set of software components, system build and development tools created to ease the development to be done on top of STM32MPU devices. 

STM32MPU Embedded Software distribution includes: 
* A Linux® distribution, running on the Arm® Cortex®-A processor(s)
* A STM32Cube Package, running on the Arm® Cortex®-M processor

**OpenSTLinux distribution** is a Linux® distribution based on the OpenEmbedded build framework.
It includes the following collection of software components. 
* OpenSTLinux BSP (OP-TEE secure OS, boot chain and Linux kernel): 
  * The boot chain based on TF-A and U-Boot 
  * The OP-TEE secure OS running on the Cortex®-A in secure mode 
  * The Linux kernel running on the Cortex®-A in non-secure mode 
* Application frameworks such as the following Linux application frameworks (non-exhaustive list): 
  * Wayland-Weston as a display/graphic framework 
  * Gstreamer as a multimedia framework 
  * Advanced Linux Sound Architecture (ALSA) libraries 

**STM32Cube™** is a comprehensive embedded software libraries and drivers, delivered for each STM32 series.
   * The CMSIS modules (core and device) corresponding to the Arm® core implemented in this STM32 product
   * The STM32 HAL-LL drivers : an abstraction drivers layer, the API ensuring maximized portability across the STM32 portfolio 
   * The BSP Drivers of each evaluation or demonstration board provided by this STM32 series 
   * A consistent set of middlewares components such as RTOS, OpenAMP, ...
   * A full set of software projects (basic examples, applications or demonstrations) for each board provided by this STM32 series

**STM32-TFM-MPU** is the secure firmware package for STM32MP25 coproc.
   * Trusted Firmware-M software (TF-M) 
   
## Description

This repo is a simple Readme describing all STM32MP25 related GitHub projects, the open source offer for the STM32 MPU products.

### STM32MPU Embedded Software packages 
STM32MP25 Packages (specific) | Description
---------------------- | -----------
[oe-manifest](https://github.com/stm32mpu-oem/oe-manifest) | STM32MP25 Embedded Software overall manifest
[meta-st-stm32mp](https://github.com/stm32mpu-oem/meta-st-stm32mp) | STM32MP25 OpenEmbedded/Yocto BSP layer
[meta-st-stm32mp-addons](https://github.com/stm32mpu-oem/meta-st-stm32mp-addons) | STM32MPU OpenEmbedded/Yocto BSP layer addons (CubeMX machine, ...)
[linux](https://github.com/stm32mpu-oem/linux) | STM32MP25 linux kernel on ***-stm32mp25 branch**
[u-boot](https://github.com/stm32mpu-oem/u-boot) | STM32MP25 u-boot on ***-stm32mp25 branch**
[arm-trusted-firmware](https://github.com/stm32mpu-oem/arm-trusted-firmware) | STM32MP25 arm trusted firmware on ***-stm32mp25 branch**
[optee_os](https://github.com/stm32mpu-oem/optee_os) | STM32MP25 OPTEE OS on ***-stm32mp25 branch**
[SCP-firmware](https://github.com/stm32mpu-oem/SCP-firmware) | STM32MP25 System Control Processor (SCP)
[dt-stm32mp](https://github.com/stm32mpu-oem/dt-stm32mp) | STM32MP25 external device tree component
[gcnano-binaries](https://github.com/stm32mpu-oem/gcnano-binaries) | STM32MP25 GPU binaries, GPU kernel driver source code
[STM32CubeMP2](https://github.com/stm32mpu-oem/STM32CubeMP2) | STM32MP2 Cube non secure co-processing firmware
[trusted-firmware-m](https://github.com/stm32mpu-oem/trusted-firmware-m) | STM32MP25 Trusted Firmware-M software implementation
[tf-m-tests](https://github.com/stm32mpu-oem/tf-m-tests) | STM32MP25 TF-M tests implementation


STM32MPU Packages (common) | Description
---------------------- | -----------
[meta-st-scripts](https://github.com/STMicroelectronics/meta-st-scripts) | STM32MPU OpenEmbedded/Yocto front-end scripts
[meta-st-openstlinux](https://github.com/STMicroelectronics/meta-st-openstlinux) | STM32MPU OpenEmbedded/Yocto frameworks layer (demonstrators, images examples, ...)
[linux-examples](https://github.com/STMicroelectronics/linux-examples) | STM32MPU linux examples
[optee-stm32mp-addons](https://github.com/STMicroelectronics/optee-stm32mp-addons) | STM32MPU features and add-ons around the OP-TEE ecosystem

### STM32MPU Tools packages 
STM32MP25 Packages (specific)| Description
---------------------- | -----------
[STM32DDRFW-UTIL](https://github.com/stm32mpu-oem/STM32DDRFW-UTIL) | STM32MP25 firmware used to initialize DDR and perform DDR tests
[STM32PRGFW-UTIL](https://github.com/stm32mpu-oem/STM32PRGFW-UTIL) | STM32MP25 multiple applications to manage the One-time Programmable (OTP)
[stm32wrapper4dbg](https://github.com/stm32mpu-oem/stm32wrapper4dbg) | STM32MP25 tool that adds a debug wrapper to a stm32 fsbl image

### STM32 MPU OpenSTLinux Expansion Packages 
STM32MP25 Packages (specific)| Description
---------------------- | -----------
[X-LINUX-AI](https://github.com/stm32mpu-oem/meta-st-x-linux-ai) | OpenEmbedded meta layer to install AI frameworks and tools for the STM32MP25 
X-LINUX-TSNSWCH | OpenEmbedded meta layer for x-linux-tsn-swch expansion package for the STM32MP25 (under TTTech License aggreement, delivered on request)
X-LINUX-ACM| OpenEmbedded meta layer for x-linux-tsn-acm expansion package for the STM32MP25 (under TTTech License aggreement, delivered on request)

## Communication and support 
STM32MP25 WIKI = https://wiki.st.com/stm32mp25-beta-v5/wiki/Main_Page<br>
Or <br>
Contact your local ST support Team
