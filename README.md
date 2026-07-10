# RPG Engine Demo
This is a rough demo made to showcase my RPG engine. Text elements and instruments are custom, everything else is placeholder. I used the village map from Harvest Moon on the SNES as a test case as that game already had tilesets with seasonal differences.

# Controls
* A Button - Talk to people, advance text, interact with environment
* B Button - hold to run
* L Button - Decrease RTC time by 30 minutes
* R Button - Increase RTC time by 30 minutes
* Start - Cycle seasons (can only be done indoors, changes appreciable on map load)
* Select - Toggle brightness settings
* \+ Control Pad - moves your character, even diagonally!

# Features
* Time of day and seasons are tracked in real time, allowing maps to have dynamic tilesets and lighting
* Custom dynamic lighting system allows for real time palette adjustments base on time and season. I'm really proud of this one!
* NPC event system which allows for random movement or movement along a specific path
* Robust text engine which allows for different styles of textboxes and font colors, as well as audio triggers
* Full featured tile and palette animation system, as can be seen in various maps in the demo.
* Metatile-specific interactions such as clocks, bookshelves, and many other map elements. Try pressing A on things!
* That's pretty much it, so far it's just your basic top down engine otherwise, heh.

Please enjoy and let me know if you encounter any bugs or oddities or have any other issues.

# IMPORTANT
***PLEASE NOTE THAT REAL-TIME CLOCK FEATURES MAY NOT WORK AS INTENDED ON SOME EMULATORS.***

Most emulators, with the exception of Mesen which breaks from April through November (...yes, really), won't allow you to set the date and time via the in-game interface and will in fact ignore the hardware commands to do so. They usually opt to instead use your system date and time, and as such, you may not be able to set the date/time directly or advance time using L/R. Playing on real hardware (i.e. a real-time clock compatible flash card) will always work correctly--as does manually changing your computer's date/time. You *can* also use Mesen as long as you set a date from December - March.

If you're wondering about the Mesen issue, it seems that specific months (April through November) will cause an overflow, and the emulator will increment the clock's *hours* every second, rather than...well, seconds. I don't know the specifics as to why this happens under the hood, but it appears to be an emulation bug as this *does* seem to work correctly on real hardware. If you happen to play on a flash cart, please let me know if you discover otherwise.
