# Lab 9 - Sensors

## Introduction

In this lab you will build an app that displays a ball that the user can control by tilting the device. You will also learn about low- and high-pass filters.

You won't be able to test this app on the emulator. If you don't have an Android device, you should choose a partner who does.

## Useful Links

The following documentation might be helpful for this lab.
* http://developer.android.com/guide/topics/sensors/sensors_overview.html
* http://developer.android.com/guide/topics/sensors/sensors_motion.html

## Final Words

* When using sensor data to display data on the screen it is important to keep in mind the differences between the sensor coordinate system and the screen coordinates
  * We've simplified things is this lab by locking the app to landscape mode and assuming the natural orientation of the device is portrait
  * The app probably won't run correctly on a device that has landscape mode as its natural orientation
  * You can, however, easily tweak the app to work on such a device

You can read more about this issue here: http://android-developers.blogspot.ca/2010/09/one-screen-turn-deserves-another.html

**Lab Todo**

Read the skeleton code and make sure you understand what it's doing. The code will be somewhat familiar to you. This lab is based on the previous lab, the "bubbles" lab.

Complete the TODOs in `BubbleActivity`.  Have fun!

**Lab Completion**

* Submit the completed `BubbleActivity.java` file to the D2L drop box
* Keep a copy of your project work and answers for future reference
