# W.O.P.R. Display

Forked from [the original](https://github.com/UnexpectedMaker/wopr) to add some extra settings, and add support for fetching data from my [GNSS "War Room"](https://github.com/autumn-mck/gnss-war-room) project

![codes](https://3sprockets.com.au/um/projects/wopr/wopr_codes.gif)

# Setup

Using some features (Displaying time, GNSS data) requires connecting to WiFi.

Connect the WOPR via USB, and open the `WOPR_Display_V2` folder in the arduino IDE. Make sure "UM TinyS3" is selected as the board, and is detected. Modify `secret.h` to have the correct SSID and password.

(Note: may not work with QUB wifi as it usually wants a username too, I used my hotspot in the demo just to be safe)

If using for GNSS data, you'll need to modify the API URL currently hardcoded in the `.ino` file from `gnss.mck.is`

Finally, upload the code to the WOPR. (ctrl+U or the upload button in the IDE)

# Instructions

Button 1 (right button) in menu to go through list of modes  
Button 2 (left button) to select mode  
When in a mode, button 1 will exit to the menu

In settings mode, button 1 switches which setting you are on, button 2 changes the current settings value

Hold Button 1 to save/exit settings. Display will show "saving..." when triggered.
