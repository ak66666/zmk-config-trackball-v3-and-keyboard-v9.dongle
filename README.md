# ThumbsUp! Trackball v3 and ThumbsUp! Keyboard v9 work together through a dongle!

Borrowed the code from https://github.com/kaihchang/zmk-config-kai-cosmos-dongle

Added the ThumbsUp! v9 keyboard to the trackball configuration:
https://github.com/ak66666/zmk-config-trackball.v3.dongle 
https://github.com/ak66666/zmk-config-thumbsup


Keyboard supports ProGlide Cirque touchpad. 
All the functions of the keyboard and the trackball are preserved.

This firmware works even if one of the devices (Peripherals in ZMK parlance) is missing or turned off.
It can be used for keyboard without the trackball, and vice versa.
I.e. I don't need to prepare a separate package for v9 board with the dongle, will use this one.

![Photos](https://github.com/ak66666/zmk-config-trackball-v3-and-keyboard-v9.dongle/blob/main/photos/20250917_Keyboard_Trackball_Dongle.jpg)

From kai-cosmos:
What's good about ZMK dongles?<br/>
- Almost immediate connection and wake-up from sleep mode.<br/>
- No more dependent from less stable Bluetooth connections.<br/>
- Extended battery life for both splits/peripherals.<br/>
- "Wireless" support for ZMK studio, able to change keymaps on the fly.<br/>

Surely there's something bad?<br/>
- Extra cost for a spare MCU, seeeduino nrf52840 sense in my case here.<br/>
- Takes up an extra USB slot on your device.

(end of quote)
