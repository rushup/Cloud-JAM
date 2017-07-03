# Cloud-JAM

![](https://raw.githubusercontent.com/rushup/Cloud-JAM/master/JAM-TOP.jpg)

Cloud-JAM is the product accelerator (production grade solution) of ST functional pack P-NUCLEO-CLD1 that combines:

-  NUCLEO F401RE
-  NUCLEO SHIELD IKS01A2
-  NUCLEO SHIELD NFC01A1
-  NUCLEO SHIELD IDW01M1

At a firmware level the Cloud-Jam works the same way as those 4 hardware combined.

So any project or binary created for STM32F401RE microcontroller can run or be debugged on the Cloud-JAM.

You can find functional pack applications and sources [HERE](http://www.st.com/en/evaluation-tools/p-nucleo-cld1.html)
or if you are not familiar with stm32 check the [Getting started guide](https://github.com/rushup/Cloud-JAM/wiki/Getting-started-with-Cloud-JAM)

# FAQ

**What's different between Cloud-JAM and Cloud-JAM L4?**

Cloud-JAM is based on an STM32F401RE, Cloud-JAM L4 on a STM32L476RG. You should check the datasheet of the microcontroller for detailed informations.

The main differences are:

|          | Cloud-JAM | Cloud-JAM L4|
|---------|-------------|-----------|
|Flash Memory| 512KB | 1MB|
|SRAM| 96KB | 128KB|
|Expansion connetor| I2C, UART, GPIOs | 4 GPIOs|
|USB cable provided| No | Yes |


# More

[rushup.tech](http://rushup.tech/)

<a href="https://catalog.azureiotsuite.com/details?title=Cloud_JAM">
<img src="https://raw.githubusercontent.com/wiki/rushup/kitra/azure-res/Microsoft_Azure_Certified_RGB.png">
</a>

