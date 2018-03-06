---
title: Voltage Protocol
---

## How to create a voltage control protocol

Open up the voltage protocol dialog by clicking the menu `Edit > Voltage`

If you've gone through the [Getting Started]() tutorial, you're no doubt familiar with this table.

Two types of voltage epochs are available: steps and ramps. As you've probably guessed, in a step epoch the voltage jumps from one level "simultaneously" (i.e. within a single AD interval). In ramp epochs, the voltage changes linearly throughout the ramp from the starting value to the ending value. At the beginning of a ramp, the voltage will be stepped to the starting voltage. At the end of the ramp, the voltage will remain at the ending voltage until the next epoch (which could of course be right away).
