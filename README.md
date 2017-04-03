# android-nav-hud
Tasker project for displaying a HUD on a local or remote device, using data from Google Maps navigation.



## Requirements
 - Android device(s)
 - Tasker
 - AutoNotification
 - AutoTools
 - PAW Server

## Setup

#### Sender

1. Install and set up the required apps to your liking.
2. Copy the files from the `html` folder into PAW's `html` folder.
3. Import the project into Tasker.
4. Adjust the triggers for `HUD Toggle` to your liking.
5. Apply! (Yay! Tasker finally has that!)
6. Start Google Maps and set it to navigate somewhere.

#### Receiver

1. Install and set up Tasker and AutoTools.
2. Create a new task.
3. Add an AutoTools Web Screen.
4. Set Source to `http://localhost:8080/hud.html` (For remote use, find your sender device's IP address and use that instead of `localhost`).
5. Run it!
