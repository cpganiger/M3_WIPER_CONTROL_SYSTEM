### PROBLEM STATEMENT

The setup consists of Blue, Green and Orange LEDs

·The three LEDs must come on and OFF alternately for set frequency

· State A shows RED led will be ON

1.Ignition Key Position at ACC: The Red LED is ON, if the user button is pressed and held for 2 secs

2.Wiper ON: Wiper is OFF: On press of the user input, Blue, Green and Orange LEDs come ON one at a time with the set frequency, The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz

3.Wiper OFF: Wiper is ON: The LED glow pattern stops on the 4th press; the wiper action starts next press onwards as mentioned in step 2

4.Ignition Key Position at Lock: The Red LED is OFF, if the user button is pressed and held for 2 secs

## COMPONENTS AND FEATURES

# STM32F407VG Microcontroller Board
STM32F407xx family is based on the high-performance Arm® Cortex®-M4 32-bit RISC core operating at a frequency of up to 168 MHz. The Cortex-M4 core features a Floating point unit (FPU) single precision which supports all Arm single-precision data-processing instructions and data types. It also implements a full set of DSP instructions and a memory protection unit (MPU) which enhances application security.
The STM32F405xx and STM32F407xx family incorporates high-speed embedded. It has upto 1 Mbyte of Flash memory, 192+4 Kbytes of SRAM including 64-Kbyte of CCM (core coupled memory) data RAM,512 bytes of OTP memory,Flexible static memory controller supporting Compact Flash, SRAM, PSRAM, NOR and NAND memories. It has 3 V and 5 V external application power supply.

# Software Requirements
STM32 CUBE IDE is used for the software simulation. STM32CubeProgrammer (STM32CubeProg) provides an all-in-one software tool to program STM32 devices in any environment: multi-OS, graphical user interface or command line interface, support for a large choice of connections (JTAG, SWD, USB, UART, SPI, CAN, I2C), with manual operation or automation through scripting.

### SWOT ANALYSIS

## Strengths

1. Works Faster – ARM performs single operation at a time. This makes it work faster.

2. It has lower latency that is quicker response time

3. Better Battery Life – ARM Processors have better battery life. This is seen from administering devices that use ARM processors and those that do not. Those that used ARM processors worked for longer and got discharged later than those that did not work on ARM processors.

4. Less Power Consumption 

## Weakness

1. It requires skilled programmers

2. Cost of implementation becomes high due to use of sensors
 
## 4'W & 1'H

# Who

Anyone who has the need to control the operational speed of a wiper in accordance with rain conditions

# What

It is a Wiper Speed Control System programme for all automobiles.

# Why

For safe and comfortable driving during bad weather conditions alongwith an advantage of ARM based microcontroller 

# When

In difficult environmental conditions, such as a rainy climate,

# How

After wiping the windsheet of motor vehicles, the LED displays the position of the wiper and returns to its normal state.

# Requirements

High level requirements|ID	Discription	status
----|--------------
HR_01	Lock and Unlock of car|Implemented
HR_02	be able to ON the wipers and control their speed|Implemented
HR_03	Activating the Wiper System|Implemented
HR_04	Deactivating the Wiper System|Implemented

# Low level requirements

Low level requirements|ID	Discription	status
----|--------------
LR_01	If the Button pressed ONCE - ON RED LED|Implemented
LR_02	If the Button pressed TWICE - OFF RED LED|Implemented
LR_03	If the Button pressed THRICE - ON BLUE,GREEN,ORANGE LEDs|Implemented
LR_04	If the Button pressed FOUR times - ON ORANGE,GREEN,BLUE LEDs|Implemented
