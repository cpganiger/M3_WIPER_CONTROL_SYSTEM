### INTRODUCTION

Wiper is an essential component that used to wipe the raindrops or any water from the windscreen. Wipers are designed and made to clear the water from a windscreen. Most of cars have two wipers on the windscreen, one on the rear window and the other on each headlight. The wiper parts visible from outside the car are the rubber blade, the wiper arm holding the blade, a spring linkage, and parts of the wiper pivots. The wiper itself has about six parts called pressure points or claws that are small arms under the wiper.

### PROBLEM STATEMENT

The setup consists of Blue, Green and Orange LEDs

·The three LEDs must come on and OFF alternately for set frequency

· State A shows RED led will be ON

1.Ignition Key Position at ACC: The Red LED is ON, if the user button is pressed and held for 2 secs

2.Wiper ON: Wiper is OFF: On press of the user input, Blue, Green and Orange LEDs come ON one at a time with the set frequency, The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz

3.Wiper OFF: Wiper is ON: The LED glow pattern stops on the 4th press; the wiper action starts next press onwards as mentioned in step 2

4.Ignition Key Position at Lock: The Red LED is OFF, if the user button is pressed and held for 2 secs

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

