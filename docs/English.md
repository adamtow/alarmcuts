# AlarmCuts
AlarmCuts faciliates the recording and management of sounds that can be used as alarms to automatically trigger your shortcuts.

![AlarmCuts and Clock](https://adamtow.github.io/alarmcuts/images/alarmcuts-clock.png)

## Overview
Did you know that you can create alarms with custom ringtones that  can automatically run shortcuts using Siri Shortcut phrases? You can, and AlarmCuts helps you with this multi-step process involving GarageBand, Clock, and Shortcuts.

***

## Download and Installation
Download the latest version of AlarmCuts from RoutineHub:

> [**Download AlarmCuts from RoutineHub &raquo;**](https://routinehub.co/shortcut/2071)

## Usage


## Creating Ringtones in GarageBand
Once you have recorded a Siri phrase for your shortcut, you can open GarageBand to create your ringtone.

![AlarmCuts and GarageBand](https://adamtow.github.io/alarmcuts/images/alarmcuts-garageband.png)

> If you are running an iOS device that supports Slide Over, tap **Open GarageBand and Help**. This will open both GarageBand and AlarmCuts Documentation in Safari. Next, place Safari in Slide Over mode on top of GarageBand. You can then follow the instructions below while you create your ringtones.

Tap **Open GarageBand** and follow these steps:

![GarageBand Home](https://adamtow.github.io/alarmcuts/images/garageband-home.png)

- Tap **+** to create a new song.

![GarageBand Instrument - Audio Recorder](https://adamtow.github.io/alarmcuts/images/garageband-instrument.png)

- Choose **Audio Recorder** in the list of instruments.
- Tap the **Tracks** button to go to the Track View screen for the song.

![GarageBand Tracks Button](https://adamtow.github.io/alarmcuts/images/garageband-tracks-button.jpg)

![GarageBand Track View](https://adamtow.github.io/alarmcuts/images/garageband-trackview.png)


![GarageBand Loops](https://adamtow.github.io/alarmcuts/images/garageband-loops.png)

![GarageBand Import Files](https://adamtow.github.io/alarmcuts/images/garageband-import-file.png)

![GarageBand File Imported](https://adamtow.github.io/alarmcuts/images/garageband-file-imported.png)

![GarageBand File in Track View](https://adamtow.github.io/alarmcuts/images/garageband-file-track.png)

![GarageBand Long Press to Bring up Share Menu](https://adamtow.github.io/alarmcuts/images/garageband-long-press.png)

![GarageBand Save as Ringtone](https://adamtow.github.io/alarmcuts/images/garageband-ringtone.png)

![GarageBand Setting Ringtone Name](https://adamtow.github.io/alarmcuts/images/garageband-ringtone-name.png)

## Clock

## Settings

***

## Limitations
If an alarm goes off when your iOS device is locked, some shortcuts may not work properly or will ask you to unlock the device before continuing. 

Shortcut actions that require the device to be unlocked before they can run include:

- Health
- Get Current Location
- Get Current Weather
- Open App
- Continue in Shortcut
- Dictation

You'll want to practice running your shortcut while your device is locked to see if it will work properly with AlarmCuts by doing the following:

1. Wait a Wait action of 5 seconds to the beginning of your shortcut.
2. Run your shortcut.
3. Press the Sleep/Wake button on your iOS device to lock it.

If your shortcut runs properly, it should be able to run when used with the Clock app. If not, you'll have to rewrite your shortcut for it to work.

### Lock Detection
Since the screen is on when the alarm goes off, you cannot use the lock detection technique of checking if the screen brightness is 0 to determine if the device is locked. 

***

## Version History

- **February 24, 2019**: Initial release.

***

## License
Copyright © 2019 Adam Tow • tow.com • @atow

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.