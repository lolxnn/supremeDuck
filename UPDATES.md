**10/05/2018 - 6pm**  
-added Alt+Tab  
-added arrow keys in "Plain text" and "Execute program" categories  
-fixed Enter button bug  

**10/05/2018**  
-updated mobile app  
-adding/editing/removing presets is now available through the following ways:  
1. Directly from "Categories -> Manage presets" menu  
2. By modifying files at "/supremeDuck_data/presets/custom_Category.txt" (for all categories except ducky scripts)  
3. By adding/modifying files at "/supremeDuck_data/ducky_scripts/" (ducky scripts only, files must have .txt extension)  

**06/04/2018**  
-organized mit app inventor project (collapsed all the blocks so they're close together now, don't lag as much and are much easier to handle)  
-fixed small bug  
-moved comments to the side in the code because they made it less readable 

**02/09/2017**  
-fixed Arduino code bug, in some language settings "Enter" and other key modifiers were substituted with other keys(thanks to HydrexHD who reported it)  

**19/08/2017**  
-added new presets, ducky scripts (also moved them from pastebin into github), youtube videos (songs + bunch of "one liners") and websites (bunch of gifs)  
-removed few not working presets (kind of dead links)  
-added "Settings" category in the mobile app  
-added version check. After picking the bluetooth device and connecting to it the version check will be performed to make sure that the movile app version is the same as the Arduino code version. Notification will be displayed if these don't match. (This feature will work only from version 1.03 and newer)  
-further simplified the MIT app inventor 2 project (supremeDuck.aia) 

**14/08/2017**  
-added ability to use "ducky script" ("PAUSE", "BREAK", "DEFAULTDELAY", "PRINTSCREEN", "SCROLLLOCK" are not implemented though)  
-fixed minor bugs  
-simplified some of the MIT app inventor 2 components (implemented global lists variables instead of using countless "if then else" statements, the lists are located around the bottom of the project "block canvas" and can be easily edited/expanded)  

**12/08/2017**  
-Just to let you know I'm still working on this project, it isn't just published and left. Soon it should be able to use the "ducky script" language. Also the MIT app inventor app will probably become easier to modify and it will be easier to add your own presets. Currently it seems like a mess, mostly because I was new to it when I started building the app.

**06/08/2017**  
-fixed minor bugs

**04/08/2017 - 18:50**  
-the application is now available in the Google Play Store :) [link](https://play.google.com/store/apps/details?id=appinventor.ai_michalmonday17.supremeDuck)

**04/08/2017 - 13:30**   
-decreased buffer size of encoding data (it was unnecessarily big)  
-used F() function for debugging strings (so now they are stored in flash memory instead of the dynamic memory)  

Both changes prevent the "Low memory, stability issues may occur" warning in Arduino IDE.  


**04/08/2017**  
-implemented 2-way communication so now the arduino tells the mobile app about its current language setting and whether it uses "MultiLang" method  
-added built in web browser so it's possible to search funny images around the internet and copy url by a button (there's also a button to extract Youtube video ID that is currently in the browser)  
-fixed small bug regarding "MultiLang" method (upper case were not affected by it till now)  

![pic](http://i.imgur.com/Hu1tfxg.png)  

![Pic](http://i.imgur.com/CiTAJom.png)
