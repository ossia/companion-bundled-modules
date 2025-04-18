## Mitti

**Basic Configuration**

- In Mitti > Settings... > OSC/UDP Controls, select "Enable"
- In the configuration page for the Mitti module in Companion, enter the IP address of the computer running Mitti

**Enabling Button Variables & Feedback**

- In Mitti > Settings... > OSC/UDP Controls, select **Companion-Mitti-Module** from the **Feedback To** dropdown
- If **Companion-Mitti-Module** is not an option, select **Custom** then follow the next steps:
  - For **IP** enter the IP address of the computer running Companion
  - For **Port** enter the port number that is present on the configuration page for the Mitti module in Companion. By default port `51001` is used
- _Optional: Enable **Feedback Alert** in the Companion module settings. This will show an error when Companion does not receive feedback from Mitti. Disable this feature if you do not plan on using the Feedback features._

![Mitti](images/mitti.png?raw=true 'Mitti')

**Available Actions**

- Play
- Toggle Play
- Stop
- Panic
- Rewind
- Jump to previous cue
- Jump to next cue
- Jump to specific cue
- Jump to selected cue
- Jump to cue with name
- Select previous cue
- Select next cue
- Goto 30
- Goto 20
- Goto 10
- Play Selected Cue
- Play cue with number / ID
- Play cue with name
- Play cue at index
- Toggle Fullscreen
- Fullscreen On
- Fullscreen Off
- Toggle Playlist Loop
- Playlist Loop On
- Playlist Loop Off
- Toggle Playlist Transition on Play
- Transition on Play Off
- Transition on Play On
- Resend OSC Feedback

_Requires Mitti 2_

- Cue Scale
- Cue Position
- Cue Crop
- Cue Rotation
- Cue Hue
- Cue Saturation
- Cue Vibrance
- Cue Brightness
- Cue Contrast
- Cue Opacity
- Set Cue Volume to Value
- Cue Playback Speed
- Adjust Current Cue Volume
- Toggle Goto Cue after End
- Goto after End On
- Goto after End Off
- Set Goto after End Cue
- Master Fader
- Toggle / On / Off Video Outputs
- Toggle / On / Off Audio Outputs
- Adjust Playhead
- Scrub Playhead with Timecode
- Set In / Out from Playhead

**Available Feedback**

- Play/Pause Status
- Cue Name - Playing
- Cue Name - Active
- Cue Name - Selected
- Cue ID - Playing
- Cue ID - Active
- Cue ID - Selected
- Cue ID - Audio Enabled
- Cue ID - Pause at Beginning Enabled
- Cue ID - Pause at End Enabled
- Cue ID - Fade In Enabled
- Cue ID - Fade Out Enabled
- Cue ID - Loop Enabled
- Cue ID - Transition Enabled
- Cue ID - Goto Enabled
- Set In / Out from Playhead Available
- Time Remaining on Playing Cue
- Video Outputs Active (requires Mitti 2)
- Audio Outputs Active (requires Mitti 2)

**Available Variables**

- currentCueName
- currentCueID (requires Mitti 2)
- previousCueName
- nextCueName
- selectedCueName
- selectedCueID (requires Mitti 2)
- playStatus
- cueTimeLeft (will shorten to MM:SS if less than 1 hour)
- cueTimeLeft_hhmmss (will always show full HH:MM:SS timecode)
- cueTimeLeft_h
- cueTimeLeft_m
- cueTimeLeft_s
- cueTimeElapsed
- cueTimeElapsed_hhmmss
- cueTimeElapsed_h
- cueTimeElapsed_m
- cueTimeElapsed_s
- currentCueTRT (will shorten to MM:SS if less than 1 hour)
- currentCueTRT_hhmmss (will always show full HH:MM:SS timecode)
- currentCueTRT_h
- currentCueTRT_m
- currentCueTRT_s
- currentCueAudio
- currentCuePauseAtBeginning
- currentCuePauseAtEnd
- currentCueFadeIn
- currentCueFadeOut
- currentCueLoop
- currentCueTransition
- currentCueGoto
- cue\_(number)\_cueName (requires Mitti 2)
- cue\_(number)\_audio (requires Mitti 2)
- video_outputs (requires Mitti 2)
- audio_outputs (requires Mitti 2)
