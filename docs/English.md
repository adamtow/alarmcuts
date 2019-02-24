# AlarmCuts
AlarmCuts faciliates the recording and management of sounds that can be used as alarms to automatically trigger your shortcuts.

Did you know that you can create alarms with custom ringtones that  can automatically run shortcuts using Siri Shortcut phrases? You can, and AlarmCuts helps you with this multi-step process involving GarageBand, Clock, and Shortcuts.

![AlarmCuts and Clock](https://adamtow.github.io/alarmcuts/images/alarmcuts-clock.png)

## Table of Contents
- [Download and Installation](#download)
- [AlarmCuts Interface](#alarmcuts)
	- [Recording a New Sound](#record)
	- [Trimming a Sound](#trim)
	- [Deleting a Sound](#delete)
- [Creating Ringtones in GarageBand](#garageband)
- [Creating Alarms in Clock](#clock)
- [Alarm Tips](#tips)
	- [Limitations](#limitations)
- [Settings](#settings)
- [Localization](#localization)
- [Version History](#version)
- [License](#license)

***

<span id="download"></span>
## Download and Installation
Download the latest version of AlarmCuts from RoutineHub:

> [**Download AlarmCuts from RoutineHub &raquo;**](https://routinehub.co/shortcut/2071)

***

<span id="alarmcuts"></span>
## AlarmCuts Interface
When you launch AlarmCuts, the AlarmCuts Home screen will appear with the following items:

- **Record New Sound**: Record a new sound that will be converted to a [ringtone in GarageBand](#garageband) and used as the [alarm sound in Clock](#clock).
- **Open GarageBand**: Opens the GarageBand application.
- **Open Clock**: Opens the Clock application.
- **Sounds**: A list of the sounds that you have created in AlarmCuts. These sounds are located in the `iCloud Drive/Shortcuts/AlarmCuts/sounds` folder.
- **About**: Displays the AlarmCuts About screen that displays the version string and build number.
- **Help**: Displays the documentation that you are reading now.
- **Settings**: Open the [AlarmCuts Settings](#settings) menu.

![AlarmCuts Interface](https://adamtow.github.io/alarmcuts/images/alarmcuts-interface.png)

<span id="record"></span>
### Recording a New Sound
- Tap **Record New Sound** to create a new audio recording. If **Display Hints** is enabled, an alert will appear providing instructions on the steps it will take to record the sound and convert.
- Tap the screen to start recording your Siri Shortcut phrase. Speak the phrase quickly so that when your alarm goes off, iOS hears the whole phrase and doesn't stop your alarm sound prematurely. See the [Tips section](#tips) for more details.
- Tap the screen to stop recording.

![AlarmCuts Record (1/2)](https://adamtow.github.io/alarmcuts/images/alarmcuts-record-1.png)

- Next, enter the name for the new audio recording. It's recommended you use the name of the shortcut.
- If a file with the same name exists in the `iCloud Drive/Shortcuts/AlarmCuts/sounds` folder, you will be prompt to replace the file, keep both audio files, or skip. If you choose skip, the audio recording will not be saved.
- After the file has been saved, you will have the opportunity to open [GarageBand](#garageband) to create a ringtone that can be used with alarms in the Clock app.

> If you are running an iOS device that supports Slide Over, tap **Open GarageBand and Help**. This will open both GarageBand and AlarmCuts Documentation in Safari. Next, place Safari in Slide Over mode on top of GarageBand. 

![AlarmCuts Record (2/2)](https://adamtow.github.io/alarmcuts/images/alarmcuts-record-2.png)

<span id="trim"></span>
### Trimming a Sound
You can trim the audio recording after the fact by tapping **Trim Sound** from the Sound Edit screen.

<span id="delete"></span>
### Deleting a Sound
Delete a sound by tapping **Delete Sound** from the Sound Edit screen. You will be asked to confirm deletion. This operation cannot be undone.

***

<span id="garageband"></span>
## Creating Ringtones in GarageBand
Once you have recorded a Siri phrase for your shortcut, you can open GarageBand to create your ringtone.

![AlarmCuts and GarageBand](https://adamtow.github.io/alarmcuts/images/alarmcuts-garageband.png)

Follow these steps in GarageBang to create a ringtone:

![GarageBand Home](https://adamtow.github.io/alarmcuts/images/garageband-home.png)

- Tap **+** to create a new song.

![GarageBand Instrument - Audio Recorder](https://adamtow.github.io/alarmcuts/images/garageband-instrument.png)

- Choose **Audio Recorder** in the list of instruments.
- Tap the **Tracks** button to go to the Track View screen for the song.

![GarageBand Tracks Button](https://adamtow.github.io/alarmcuts/images/garageband-tracks-button.png)

![GarageBand Track View](https://adamtow.github.io/alarmcuts/images/garageband-trackview.png)

- Tap the **Loops** button.

![GarageBand Loops Button](https://adamtow.github.io/alarmcuts/images/garageband-loops-button.png)

- Tap **Files**.
- Tap **Browse Items from the Files app**.
- Navigate to the folder `iCloud Drive/Shortcuts/AlarmCuts/sounds`.

![GarageBand Loops](https://adamtow.github.io/alarmcuts/images/garageband-loops.png)

![GarageBand Import Files](https://adamtow.github.io/alarmcuts/images/garageband-import-file.png)

- Choose the audio file that you created in AlarmCuts.

![GarageBand File Imported](https://adamtow.github.io/alarmcuts/images/garageband-file-imported.png)

- Tap, hold, and drag the audio file in the Loops dialog onto the Tracks view.

![GarageBand File in Track View](https://adamtow.github.io/alarmcuts/images/garageband-file-track.png)

- Perform any editing of the audio track.
- When you are done, tap **My Songs** (iPad) or the downward-facing triangle (iPhone) to go back to the **My Songs** screen.
- Long-press on the song to bring up the editing menu.

![GarageBand Long Press to Bring up Share Menu](https://adamtow.github.io/alarmcuts/images/garageband-long-press.png)

- Tap **Share**.
- Tap **Ringtone**.

![GarageBand Save as Ringtone](https://adamtow.github.io/alarmcuts/images/garageband-ringtone.png)

- Enter the name for your ringtone. Recommendation: Name it the same as your shortcut.

![GarageBand Setting Ringtone Name](https://adamtow.github.io/alarmcuts/images/garageband-ringtone-name.png)

Now you can return to AlarmCuts to create your alarm or go straight to the Clock app.

***

<span id="clock"></span>
## Creating Alarms in Clock
Once you have created your ringtone, you can now assign it to alarms in the Clock app to automatically trigger shortcuts.

> If you are using an iOS device that supports Split View, place Shortcuts/AlarmCuts and Clock app side-by-side to see what's happening in both applications at the same time.

![AlarmCuts and Clock](https://adamtow.github.io/alarmcuts/images/alarmcuts-clock.png)

- Tap the sound you wish to create an alarm for.
- Tap **Create Alarm**.

![AlarmCuts Editing a Sound](https://adamtow.github.io/alarmcuts/images/alarmcuts-clock-edit-sound.png)

- Enter the time you want the alarm to go off and tap OK.
- Tap **OK** to open the Clock app after the alarm has been created.

![AlarmCuts Setting Alarm Time](https://adamtow.github.io/alarmcuts/images/alarmcuts-clock-alarm-time.png)

![AlarmCuts New Alarm Created](https://adamtow.github.io/alarmcuts/images/alarmcuts-clock-create-alarm.png)

- In Clock, tap **Edit**.
- Tap the alarm that was just created.

![Editing Alarm](https://adamtow.github.io/alarmcuts/images/alarmcuts-clock-edit-alarm.png)

- Disable **Snooze**.
- If desired, set the **Repeat** schedule for the alarm.
- Tap **Sound**.
- Scroll to the **Ringtones** section and choose the ringtone that you created in GarageBand. Clock will play the sound, so be prepared to disable the Siri request to prevent your shortcut from running.

![Assigning a Ringtone to your alarm](https://adamtow.github.io/alarmcuts/images/alarmcuts-clock-ringtone.png)

- Tap **Back**.
- Tap **Save**.

![AlarmCuts and Clock](https://adamtow.github.io/alarmcuts/images/alarmcuts-clock-2.png)

<span id="tips"></span>
## Alarm Tips
Here are some tips to make sure your Siri Shortcut phrases work properly when run as alarms.

- **Volume**: Make sure your alarm volume is loud enough for your iOS device can hear the Siri phrase.
- **Speed**: When you record the Siri phrase, say it quickly. If you take too long, iOS will stop playing the alarm sound and prompt you to complete the Siri phrase. After recording your sound, you can tap **Play Sound** to see if iOS accurately triggers the phrase properly.
- **Repetitions**: If iOS doesn't recognize your phrase the first time, the alarm ringtone sound will continue to play. It may recognize it on subsequent plays.
- **Background Shortcuts**: Read the section on [Limitations](#limitations) below to understand some of the problems you may face while running shortcuts from a potentially locked device.

<span id="limitations"></span>
### Limitations
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

#### Lock Detection
Since the screen is on when the alarm goes off, you cannot use the lock detection technique of checking if the screen brightness is 0 to determine if the device is locked. 

***

<span id="settings"></span>
## Settings
From the AlarmCuts Home, tap **Settings**. You can configure the following options or perform these actions from Settings:

- **Display Hints**: Displays an alert with tips before recording audio and creating the alarm.
- **Check for Updates Automatically**: When AlarmCuts is launched, it will check for updates on RoutineHub automatically.
- **Check for Updates**: Manually check for updates to AlarmCuts.
- **Back to AlarmCuts Home**: Return to the AlarmCuts Home screen.

***

<span id="localization"></span>
## Localization 
AlarmCuts is available in English, but the application is fully ready to be localized. I have developed an application, **Localization Helper**, that will assist you in localizing AlarmCuts into your language.

> [**Download Localization Helper from RoutineHub &raquo;**](https://routinehub.co/shortcut/1931)

When the localization file is complete, either submit a pull request on [my GitHub page](https://github.com/adamtow/) or [contact me](mailto:shortcuts+localization@tow.com).

***

<span id="version"></span>
## Version History

- **February 24, 2019**: Initial release.

***

## License
Copyright © 2019 Adam Tow • tow.com • @atow

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.