#[BO2] Bot Mod

###Preamble
Thanks for using my bot mod =] Approximately 70% of the code was written from scratch, so I hope you enjoy my efforts! 
Most of the code is what I have learnt over the past few months through reading the BO2 source code and observing how other people achieve different goals.

###Instructions:
1. Open up Black Ops 2 to the Custom Lobby menu and set up the game as you like.
2. Open up the .txt files and look around for any comments denoted by 2 "/"s. These are variables you can change to your liking.
3. Open "Mod Loader.exe" and find _azsry.txt.
		For the ZM mod, ensure you use the Mod Loader v2 "Asset_Loader.exe" and pick the 'zom' folder.
4. Once the files have been injected, press any button to close the program and start the game.

###Binds:
* **Use and ADS simultaneously** spawns a bot. They will spawn where you are standing and will not move unless told to in the code. Bots spawn with various weapons defined in a list with attachments and a random camo.
* **Hold Melee for ~0.5 seconds** gives yourself a weapon with any camo. Camo is defined in the code.
* **Hold Space** allows you to pick up bots once you have placed them.
* **Press 6** to suicide. Useful for returning to the map if you have fallen out of bounds or wish to change class.

###FAQs:
* My game freezes upon injecting the mod. This happens sometimes for unknown reasons. Either restart the game and inject the mod again, or set up the game how you want it and start it up to the point where you can run around, then back out and inject the mod.

* My Black Ops 2 crashes on start up after injecting the mod a few times. This seems to happen when you watch modded clips in theatre and close the game prematurely. To fix this, find "Steam\steamapps\common\Call of Duty Black Ops II\players\hardware_mp.chp" and delete it. This will reset your video settings *only*. Your controls will remain in-tact.

* My Mod Loader crashes after choosing the txt file. No definite answer to this issue has been discovered yet. Try re-extracting the .RAR archive, moving the folder to your Desktop and injecting from there, or installing .NET Framework 3.5 and 4.5 and running the injector again.

* My game does not show any signs of mods after injecting. Only one report of this has occurred to date, which was fixed by simply restarting their PC.

* More to come as the people report them.

###Credits:
* **Azsry** - Majority of code, camo selector and bot code
* **dtx12** - GSC Injector
* **Various submitters on MPGH** - Explosive Bullets, getName() function
* **Treyarch & IW** - GSC Language and additional functions exclusive to BO2

###Changelog (Latest Release: 1.0.2.5):

* 1.0.2.5
	* Added a hybrid auto-aim, which allows for both wallbangs and collaterals.
	* Added a manual suicide button, in case you fall out of the map with invincibility activated.
	* Added ZM code used for OCC 200.
	* Released publicly.

* 1.0.2.4
	* Added the ability to move bots once they have been spawned. The bots will retain their new positions.

* 1.0.2.3
	* Added random death animations when using Soft Aimbot
	* Added Soft Aimbot for grenades
	* Greatly optimised the camo code
	* Made bots always spawn on the opposite team

* 1.0.2.2
	* Removed noclip as it greatly increases the chances of receiving a VAC ban
    * Fixed bots not remaining stationary even when BotsCanMove was set to 0
	* Added a new method for Explosive Bullets which allows wallbangs

* 1.0.2.1
    * Fixed bots not copying the player's stance when set to stationary
	* Fixed noclip not working before dying once
	* Added toggle for invincibility
    
* 1.0.2.0
    * Removed deathBarrier() due to redundancy
    * Bots can now either stand, walk around or move with their normal AI
    * Allowed walking bots more freedom of movement
    * Explosive Bullets can be tweaked with labelled variables
    * Bots now respawn consistently
    * Optimised code handling bot movement and respawning
    
* 1.0.1.0
    * Fixed several crashes people were experiencing
    * Added noclip and ability to choose whether bots move around

* 1.0.0.0
    * Initial release
