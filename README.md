TheFatController
===========
The Fat Controller allows you to track trains, see their next stop, if they are currently moving and the item in their inventory with the highest count, you are also able to remotely control trains and set their schedule.

If you uninstall this mod, make sure you are out of remote control mode first unless you want to be stuck as a ghost, being a ghost is pretty cool.

Why the name?: [The Fat Controller](http://en.wikipedia.org/wiki/The_Fat_Controller)

How to use
---

Once you have researched Rail Signals a new button will show up. Pressing the button will expand the list.  
![Main UI](https://raw.githubusercontent.com/Choumiko/TheFatController/master/readme_content/TFC_main.png "Main UI")

Instantly you can see whether it is in manual mode and if the train moving, if it is running on a schedule you will see the next stop instead.  
Once the train is stopped the inventory count will update, this will display the name of the item with the highest count and "..." if there are other items in the train.  
The > or || buttons will start and stop the trains schedule and the c (control button) will put you in remote control mode.
The s button lets you filter the displayed trains by the stations in their schedule or by active alarms. The x button clears the filter.
The ! button lets you change the alarms you will be notified of. 


![Remote mode](https://raw.githubusercontent.com/Choumiko/TheFatController/master/readme_content/TFC_remote.png "Remote mode")

In remote control mode your camera will follow the train instead of the player. You should be able to click on the train and set the schedule. Clicking one of the highlighted buttons will return you to the player.

Be warned, if the player is not safe he can die, you can also run him over with the train you are remotely controlling. [i]You have been warned

Videos: [Factorio Mod Spotlight - The Fat Controller 0.0.11](https://youtu.be/zyecAmcbxtM)

#Changelog
2.0.2

 - disabled the ability to follow a train when inside a vehicle, investigating if it's a Factorio bug or not
 - added console command to try and return control to the player: /fat_fix_character

2.0.0

 - version for Factorio 0.15.x

1.0.3

 - update cargo display when leaving a station
 - fixed missing stations in the filter window
 - added a button to the alarm settings to refresh the stations in the filter window
 - added czech translation for tooltips (thanks to EnrichSilen) 
  
1.0.2

 - added tooltips to almost all buttons

1.0.1

 - fixed time between stations alert not working correctly with SmartTrains goto rules

1.0.0

 - version for Factorio 0.14.x

0.4.20

 - fixed error with Stop/Resume button

0.4.19

 - added graphics for main and player button
 - fixed Stop/Resume all not always working
