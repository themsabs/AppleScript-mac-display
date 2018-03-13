# AppleScript-mac-display

AppleScript to change the display settings of a mac. Useful for remote logging into computer via TeamViewer from a different screen-sized device.

set picture to "/Library/Desktop Pictures/Yosemite 3.jpg" //replace with your desktop image

tell application "System Events" to tell process "System Preferences" to tell window "VGA Display" //replace "VGA Display" with the name of your display, shown at the top of the System Preferences > Displays page

select row 1 //replace "1" with the row that you want your script to click on each time it is run
