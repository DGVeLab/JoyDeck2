# Installation

1. Start from the [MakerWorld project](https://makerworld.com/en/models/3316603) and read the selected JD2 release notes.
2. Download the attached Windows installer. Automatic **Source code** archives are not installers. If a portable package is offered, extract the entire folder before running `JoyDeckHub.exe` and keep its files together.
3. Install and complete free activation if requested. DGVeLab processes activation requests; allow time for the code to arrive.
4. Use firmware specifically identified for the selected JD2 release and your hardware. The documented Hub uses JoyDeck serial protocol 2. A visible COM port alone does not establish firmware compatibility.
5. Follow the firmware's flashing instructions. Use the [Flash Center](https://dgvelab.github.io/DGVeLab-Flash-Center/) only with a matching catalog entry or the release's explicit instructions. For local images, use the offsets supplied with that firmware. See [ESP-Programmer](https://github.com/DGVeLab/ESP-Programmer) for additional resources and drivers.
6. Close other applications using the serial port, reconnect USB if necessary, then start JD2.
7. Select the COM port, click **Connect** and keep the joystick centered during calibration.
8. Configure a direction, use **Test action** and **Save**.

The project's Windows x64 self-contained publish profile includes the .NET runtime. Check the actual release notes to confirm the downloaded package uses that profile.

Flashing can overwrite device settings. Export your Hub configuration before changing installation or firmware.
