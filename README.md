A fork of *Indirect*Input that enumerates joystick first. Should fix the [Controller/Wheel axis do not function correctly](https://www.pcgamingwiki.com/wiki/Need_for_Speed:_Porsche_Unleashed#Menu_lag_when_using_a_controller.2FAxes_do_not_function_correctly_.28Win8.2B.29) bug in Need for Speed Porsche Unleashed with Windows 10. Previous fixes of combining [devreorder](https://github.com/briankendall/devreorder) and [dinputto8](https://github.com/elishacloud/dinputto8) will lose force feedback when using steering wheels. Tested in Windows 10 with Logitech Wingman Formula Force GP.

Below is the original Readme.
# *Indirect*Input

![Myst 4 Screenshot](./gfx/myst4.png)

A simple DirectInput wrapper to work around a Windows 10 [device enumeration bug](https://aka.ms/AA3931c).

## Game support

- Myst 4: Revelation 1.0-1.3 (Retail disc and GOG editions)

## Install (Myst 4: Revelation)

1. Drop `dinput.dll` into the `[game root]\bin` directory.
2. You're done.

## Supported operating systems ##

- Windows 10
