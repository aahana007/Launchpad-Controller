# Launchpad-Controller to FRC Driver station
An interface for converting a Novation Launchpad Midi Signals to FRC Driver Station's vJoy buttons.

This C# Program takes midi signals from a novation launchpad and sends them to a VJoy feeder so you can use your launchpad as a FRC Driver station!

Requirements
1. Microsoft Visual Studio Community 2019 with C# package installed
2. vJoy version 2.9.1
3. FRC Driver station Dashboard version 22.0

To compile/Build on x64:
1. Make sure you have x64 directory at one level above to the directory to LaunchPad-Controller and vJoyInterface.dll and vJoyInterfaceWrap.dll from your vjoy installed directory (C:\Program Files\vJoy\x64\) are copied into it. Copy Midi.dll from \Launchpad-Controller-master\bin\Debug\ into this x64 directory.
2. Make sure all refernces to this DLL are added into the project. Otherwise build step will complain.
3. Build

To Run ON x64:
1. Plug in launchpad
2. Open FRC Driver Station Dashboard
3. Run the program!
