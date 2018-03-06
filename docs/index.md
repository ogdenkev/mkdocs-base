---
title: EasyOocyte
---

Fast and simple two-electrode voltage clamp recordings.

## Installation

### Windows

Get the [latest version](). Run the installer once it finishes downloading.

## Getting Started

This document explains how to use EasyOocyte to record ion channel currents and control solution exchange in your two electrode voltage clamp electrophysiology rig. You will learn:

* how to configure EasyOocyte with your favorite [National Intruments AD board]() and the [Warner Instruments OC-275C]() TEVC amplifier
* how to create a protocol to control a [Hamilton rotary valve]() for solution exchange
* how to create an analysis protocol to automatically measure the currents in your recordings
* how to start recording data!

### Configure EasyOocyte for your A/D board and TEVC amplifier

1. Start EasyOocyte by going to `Start > All Programs > EasyOocyte` or double click the desktop icon.
    ![]()
2. Bring up the Configure Digitize dialog box by clicking on `Configure > Digitize` in the main menu
    ![]()
3. Select your AD Board

### Create a solution protocol

In the menu, go to `Edit > Protocol` to show the solutions protocol dialog box. Here you can set up to 500 epochs of solution applications. Each row in the table configures an epoch.

### Create an analysis protocol

To set up an analysis protocol, go to the `Edit > XXX menu`. The analysis protcols are set in the table. Similar to the solution protocol, each row configures one analysis region.

### Start recording

Now that you've got the digitize set up, and specified a solution protocol and an analysis protocol, you're ready to record. Simply click the Record button. You should see the currents plotted on the recording areas. EasyOocyte will automatically save the recordings to the folder you selected with file name format YYYY-MM-DD.abf. The protocol settings will be saved alongside the recording with the .prm extension (Don't ask what it stands for, just roll with it.)

### What's next?

Learn more about [voltage protocols](voltage-protocol.html) or how to [automate the analysis](auto-analysis.html).

### Troubleshooting

Something not working? Check out our [FAQs](faq.html) to see if there's a solution.  If your answer's not there, [let us know](contact.html).

## System Requirements

* Windows XP, 7, or 10

Although all that's need to run EasyOocyte is a computer running a recent Windows operating system, you'll of course want to record some data! For that you'll also want the following:

* A National Instruments Analog-to-Digital converter (also called a digitizer or A/D board)
* A two electrode voltage clamp amplifier such as the [Warner Instruments OC-275C]()
* [Hamilton rotary valves]()

(Our favorite one is [BNC-6212]())

EasyOocyte simplifies the configuration of your 
