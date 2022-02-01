=================
Anycubic Firmware
=================

General
-------
The Anycubic Firmware is based on Marlin (https://github.com/MarlinFirmware/Marlin)

Sources
-------
The sources for the firmware of the mainboard are available on github.

Currently 3 different github projects exists for the Vyper:

#. Mainboard Firmware
    * https://github.com/ANYCUBIC-3D/Vyper
#. PlatformIO Configuration files
    * https://github.com/ANYCUBIC-3D/framework-arduinoststm32_vyper
#. Display Software
    * https://github.com/ANYCUBIC-3D/Vyper-lcd
    * Unfortunately this project doesn't contain a valid project for rebuilding or tweaking the Display application.

Build
-----

Mainboard Firmware
^^^^^^^^^^^^^^^^^^

The Mainboard can be build by following the instructions on https://github.com/ANYCUBIC-3D/Vyper/wiki

The *firmware.exe* file can be found in the git repository with the sources for the wiki.
Just clone the https://github.com/ANYCUBIC-3D/Vyper.wiki.git repository

Linux User Notes:
Anycubic provides some tools for the firmware that are Windows only.


Display
^^^^^^^
The software for creating an application for the Display is availabe in *Vyper-lcd* repository, unfortunately there
is now working project for the original display available.