## STM32MP13_EmbSW_Overall_Offer Overview

STM32MPU Embedded Software distribution is a set of software components, system build and development tools created to ease the development to be done on top of STM32MPU devices. 

STM32MP13 Embedded Software distribution includes: 
* A Linux® distribution, running on the Arm® Cortex®-A processor(s) : [OpenSTLinux distribution](https://wiki.st.com/stm32mpu/index.php/OpenSTLinux_distribution)

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

## Description

This repo is a simple Readme describing all STM32MP1 related GitHub projects, the open source offer for the STM32 MPU products.

### STM32MPU Embedded Software packages 
STM32MP1 Packages | Description
---------------------- | -----------
[oe-manifest](https://github.com/PRG-MPU-ALPHA/oe-manifest) | STM32MP1 Embedded Software overall manifest
[meta-st-stm32mp](https://github.com/PRG-MPU-ALPHA/meta-st-stm32mp) | STM32MP1 OpenEmbedded/Yocto BSP layer 
[meta-st-scripts](https://github.com/STMicroelectronics/meta-st-scripts) | STM32MP1 OpenEmbedded/Yocto front-end scripts
[meta-st-openstlinux](https://github.com/STMicroelectronics/meta-st-openstlinux) | STM32MP1 OpenEmbedded/Yocto frameworks layer (demonstrators, images examples, ...)
[meta-st-stm32mp-addons](https://github.com/PRG-MPU-ALPHA/meta-st-stm32mp-addons) | STM32MP1 OpenEmbedded/Yocto BSP layer addons (CubeMX machine, ...)
[linux](https://github.com/PRG-MPU-ALPHA/linux) | STM32MP1 linux kernel
[u-boot](https://github.com/PRG-MPU-ALPHA/u-boot) | STM32MP1 u-boot
[arm-trusted-firmware](https://github.com/PRG-MPU-ALPHA/arm-trusted-firmware) | STM32MP1 arm trusted firmware (for A7)
[optee_os](https://github.com/PRG-MPU-ALPHA/optee_os) | STM32MP1 OPTEE OS
[stm32wrapper4dbg](https://github.com/PRG-MPU-ALPHA/stm32wrapper4dbg) | STM32MP1 tool that adds a debug wrapper to a stm32 fsbl image
[Utilities-DDR](https://github.com/PRG-MPU-ALPHA/Utilities-DDR) | STM32MP1 Utitities required for DDR tuning tool
[linux-examples](https://github.com/STMicroelectronics/linux-examples) | some linux examples

## Communication and support 
Contact your local ST support Team
