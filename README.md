# flippydrive-assets (kelly-cs)
So the original repo hasn't been updated for > 1year and there's some bugs I wanted to start hitting for my own gamecube.

The original repo isn't open source, so I won't just post reverse engineered stuff here. However I will share binaries I generate for my personal gamecube. This will include changes to the flippy app or to firmware, when I find stuff worth doing.

This is not an official fork. You can use this stuff, but if you're looking  latest official FlippyDrive software can be [accessed in the releases](https://github.com/OffBroadway/flippydrive-assets/releases)

`recovery.uf2` is a special brick recovery program in case the standard update process fails for some reason.  Power off your cube, hold the button on the FlippyDrive while attaching it to USB and continue to hold until it mounts as a USB Mass Storage Device.  Copy the recovery file to the root of the drive.  It will unmount and reboot automatically.  On the next cube bootup, the update will self-extract and install automatically.
