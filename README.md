# RPG Engine Demo
This is a rough demo made to showcase my RPG engine. Text elements and instruments are custom, everything else is placeholder. I used the village map from Harvest Moon on the SNES as a test case as that game already had tilesets with seasonal differences.

# Controls
* A Button - Talk to people, advance text, interact with environment
* B Button - hold to run
* L Button - Decrease RTC time by 30 minutes
* R Button - Increase RTC time by 30 minutes
* Start - Cycle seasons (can only be done indoors, changes appreciable on map load)
* Select - Toggle brightness settings
* + Control Pad - moves your character, even diagonally!

# Features
* Time of day and seasons are tracked in real time, allowing maps to have dynamic tilesets and lighting
* Custom dynamic lighting system allows for real time palette adjustments base on time and season. I'm really proud of this one!
* NPC event system which allows for random movement or movement along a specific path
* Robust text engine which allows for different styles of textboxes and font colors, as well as audio triggers
* Tile animation system, as can be seen in various maps in the demo
* Metatile-specific interactions, such as the clocks around town/in the mayor's house, and the birdcage in the back of the restaurant
* That's pretty much it, so far it's just your basic top down engine otherwise, heh.

Please enjoy and let me know if you encounter any bugs or oddities or have any other issues.

***PLEASE NOTE THAT REAL-TIME CLOCK FEATURES WON'T WORK CORRECTLY ON MOST EMULATORS***
Most emulators, with the exception of Mesen which breaks from April through November (...yes, really), won't allow you to set the date and time directly and will in fact ignore the hardware commands to do so, opting to instead use your system date and time. As such, you may not be able to set the clock or adjust the time directly using L/R. Playing on real hardware (i.e. a real-time clock compatible flash card) will always work correctly--as does manually changing your computer's date/time. You can do the latter to check out different lighting transitions if you like, or use L/R on real hardware (or Messen if you set a date from December - March, I guess)S
