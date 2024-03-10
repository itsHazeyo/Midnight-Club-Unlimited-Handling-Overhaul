# Midnight-Club-Unlimited-Handling-Overhaul
the Definitive GTA handling mod

Convertible Summers aka itsHazeyo

Proudly Presents,
![midnight club template](https://user-images.githubusercontent.com/72316312/236901279-5bf60436-e0df-4df8-88f4-7d0018d5d709.png)
GRAND THEFT AUTO 5:

Midnight Club Unlimited

the Complete Vehicle Overhaul Mod V2

[![Watch the video](https://i.ytimg.com/vi/EUsBJwYod58/hqdefault.jpg?sqp=-oaymwE2CPYBEIoBSFXyq4qpAygIARUAAIhCGAFwAcABBvABAfgB_gmAAtAFigIMCAAQARhlIGUoZTAP&rs=AOn4CLBTYhQMqrVCICskE5AZ0yP9h6r6Sw)](https://www.youtube.com/watch?v=EUsBJwYod58)

*Features*

***ARCADEY/SIM RACE FEELING!***

***FIVEM COMPATIBLE!***

***THREE DISTINCT LEVELS OF CONTROL!***

Unlimited Pro X(Paetron/FiveM Exclusive): In addition to the changes below, I've made a more pronounced tire slip model also included are various lore friendly add-on vehicle handling profiles!

Unlimited Casual: Disabled low speed traction loss

Unlimited Filthy Casual: Closer to GTA low speed traction loss

***#LIST OF CHANGES:***
-More accurate top speed formula implemented.

-Got rid of the "sleeperfide" values in favor of a custom LS Custom script(in Development)

-Center of Mass has been adjusted to better reflect where the weight of a vehicle is.

-Drive bias changes along with the addition Drive Bias transfer to eligible vehicles.

-Standardrized shift times between vehicle classes, type, year, and transmission.

-Brake force adjustments depending on vehicle type.(Certain older vehicles will not have ABS untill you upgrage them)

-Brake Bias adjustments depending on vehicles center of mass and maxed out handbrake lock up force on every vehicle.

-Standardrized Steering lock across vehicle classes according to the table provided below (Turning radius is controled by wheel base using this method).

-Traction bias balancing to take advange of the new center of mass changes and fTractionLossMult set to 1.0 in favor of Off-Road tires via custom LS Custom script.

-Suspension changes on vehicles that exhibited "bump power".

-Adjusted swaybar "RollCenter" to maximaze center of mass changes.

-Model, Handling, and Damage Flags have been changed on various vehicles in order to better reflect their capability.

-CCarHandlingData added to every vehicle along with strAdvancedFlags changes.

-Castor added to every vehicle.

-Easter eggs

(ALL information sourced from GTA FANDOM, WIKIPEDIA, IMAGINATION and MFG SITES)
(NOT RECOMMEND FOR MOUSE AND KEYBOARD, WHEELSPIN WILL OCCUR... YOU'VE BEEN WARNED!!)

-Duplicate vehicles now have separate handling values to better reflect their differences
(I.E. Blista Compact and Go Go Monkey Blista are two very different cars now ( ͡• ͜ʖ ͡• ))

-Revamped AI to better handle vehicles (optional)



CARS 
fSteeringLock value="30.0"

DRIFT CARS
fSteeringLock value="65.00000"  #OG
fSteeringLock value="80.00000"	#CHOPSHOP

SUVS/OFFROAD/LIMOS/RALLY CARS
fSteeringLock value="35.000"

OPENWHEEL/FORMULA
fSteeringLock value="25.0"

TRUCKS/MONSTER TRUCKS
fSteeringLock value="40.0000"

FORKLIFTS
fSteeringLock value="70.000000"
fSteeringLock value="75.000000"

CERBERUS
fSteeringLock value="45.0000000"

SCARAB
fSteeringLock value="50.000000"

RAPTOR
fSteeringLock value="18.00"

MOTORCYCLES/QUADS/RCCARS
fSteeringLock value="XX.00"




KNOWN BUGS:

**-FIRST AND FOREMOST, THIS IS NOT MEANT TOO BE REALISTIC.... THE RAGE ENGINE DOES HAVE ITS QUIRKS AND FEATURES.**

-Who knew the vehicle camera was tied to the center of mass position, third person driving will look slightly different now.

-7th and 8th Gears have been removed due to the Rage engine not able to actually realize that you should be going faster in these gears.

-also Rage engine thinks transmission tuning means adding an extra gear to it rather than shorting shift times.

-This means Cars that would have 7/8 speed transmissions normally are now limited to 6.

-Which also also means you shouldn't purchase transmission upgrades as they'll most likely nerf your top-speed(if not using custom LS Custom)
-Top speeds may not be 100% spot on to their real life counter parts.

-Cars that "pop-up" wheelie unrealistically, I'm still working on the right numbers(Try a standing start in 2nd).

-You may come to a sudden stop at high speeds if you have "auto repair" enabled in any trainer.

-Grotti x80 Proto has no downforce, idk why it just won't work.

-Overflod Zeno leans like a bike?! why?

-Ocelot Virtue suspension is backwards!? again, Why?

-Don't use the Strongberd or Toreador underwater until I make a fix, got it.

-Some cars won't show full turning radius, its baked into the model.

***-Single Player is not it, The previous method of merging handing metas doesn't seem to work anymore (Hence why no manual installer) and applying the new changes to certain DLCs resulted in a CTD so many of your favorite vehicles are left out of this update. To get the full driving experience come join us on Midnight Club Unlimited FiveM server or have it installed your favorite Playground.***

RECOMMENDED MUST HAVE ADDON MODS:
-Manual Transmission, https://www.gta5-mods.com/scripts/manual-transmission-ikt
With LSD enabled

Inverse Power, https://www.gta5-mods.com/scripts/inversepower




My "Recommended" Settings:

Version 2.0.0
[Configuration]

AngleStart = 0.0

AngleStartTorqueMod = 0.0

AngleEnd = 32.0

AngleEndTorqueMod = 5.0

SpeedStart = 0.1

SpeedStartTorqueMod = 1.0

SpeedEnd = 35.0




 Version 1.1.4
[CONFIG]

Power = 100

Torque = 100

Angle = 0

Speed = 0

Slope = 0

Deadzone = 0

and vStancer, https://www.gta5-mods.com/scripts/vstancer

recommended for MAXIMUM experience in SP

RECOMMENDED FiveM MUST HAVE ADDON MODS:

Inverse Power, https://www.gta5-mods.com/scripts/inversepower

Forced induction systems compatibility build (https://github.com/itsHazeyo/renzu_turbo)

Renzu Nitro https://github.com/renzuzu/renzu_nitro

xgc/tuner, Custom compatibility build (https://github.com/itsHazeyo/xgc-tunerchip)


-issa Pista and that's a GEMREA consumer methanol cars aren't real not even in Los Santos

-Start slow and work yourself up to the Super/Hyper Cars

-Motorcycles are DEADLY

-Exclusively uploaded to github.com then gta5-mods.com be cautious of all others!

INSTALLATION:

**Game will crash if not installed correctly, always keep back-ups**
***trying to use a FiveM version in single player WILL crash your game***


Single player OIV:

1. Pick a version

2. Install the OIV

3. ????

4. Enjoy!


Optional A.I.: install to "Mods\common.rpf\data\ai" and replace "vehicleaihandlinginfo.meta"


FiveM Server:

0. Pick a version

1. Drop it into your "resource" folder

2. add "start YOURCHOICE" to your server config

3. ?????

4. Enjoy!


SPECIAL NOTE:

From now on I will be pre-releasing the mod on my Patreon/GitHub about one month in advance before I update it on gta5-mods.com
https://www.patreon.com/midnightclubunlimited

Also if you could subscribe, I already know I got your like 😋
https://www.youtube.com/@midnightclubunlimited

and follow me on instagram
https://www.instagram.com/midnightclubunlimited/


**Special Thanks to**
Rockstar, 
Take-Two,
the OpenIV team,  
GTA5-mods.com,  
FiveM team,
Alexander Blade,
ikt for vStancer and Manual Transmission,
sjaak327 for Simple Trainer,
Josh Answers,
Friends willing to test,
and players like you.


**PLAYER PREVEIW REVEWS**


"Dude, I can't wait till you put this out"

"This is how it should've been"

"This reminds me of Midnight Club"

"Bro this sh*t is immaculate"

"Heavy"

"I CRASHED SO FAST"

"Every car is actually....fun"


1.0 Release Update, Resolved 

1.2 Release Update, fixed FiveM drift pack as over 200 entries weren't set.

1.05 internal, added "_" to FiveM versions to allow for hot-swapping in console...
	May cause esx_lscustom issues until server restart. (Possible caching problem?)

1.3 internal, Removed R* "V-Tec" Flags. To buggy to use, didn't allow for smooth acceleration(even in base game).

1.4 internal, R* "Bouncy Car" bug removed, cause by a Flag.

1.5 internal, Removed/Added gearing flag modifiers on certain vehicles.

1.6 internal, Removed "Improved grip" Flags.. Didn't really do anything during testing.

1.7 internal, Added audiohash modifiers to FiveM Cayo Perico vehicles.metas to ensure working sound.

1.8 Release, Cayo Perico update.

1.8.1 Hotfix, Fixed left over code on the X80 Proto that would cause fuel drain issues with fuel mods
                and expanded the fuel tank on the Raptor as well 
				
1.8.5 Hotfix/update, Fuel tanks on chimera Trike, Outlaw buggy and open wheel class were expaned, 
                     carvariation.meta compiled for FiveM use,
		     and FlashGT was retuned. 

1.8.6 internal, Reworked the "Sleepers" formula so you WILL need a power multiplier to "Tune" its true potential
				(except the DUKES, its has 750HP on its badge) Retine MK2 was converted to a Cosworth.
				Various traction bias balances on Muscle cars that run "skinnys" up front. 

1.8.7 Release, "Wuattro" Variable AWD systems added to Obey vehicles simulating Audis' Quattro

1.8.8 Release,  Drift SZN Update. Increased the steering angle from 55 to 65 and all FF vehicles have gotten FR conversion
				along with most AWD vehicles that had over a 25/70 split.
				Fixed the Stratum in non dirft versions as it wasn't fully FF.
				Classic Sultan was Rallified in non drift versions, I.E. slight increase in steering angle.
				
1.8.9 Hotfix, Benefactor Schafter V12 was slightly overlooked and given the full BRABUS treatment.
			  also forgot to set the Drift Yosemite, Tampa, FlashGT to 65 degrees in Pro/Unlimited versions.
			  
1.9.0 Update, Los Santos Tuners cars where tuned and added, also I never realized Manual-transmission had a hard speed limiter(I should read read mes' lol.)
			  So I'm going through the vehicles and adjusting the Drag coefficient to stop the "overspeed" effect that I was not aware of till now.
			  Mostly affecting the higher speed vehicles so you may notice a slight decrease in acceleration but top speed should be the same
			  or what it should've been in the first place. Only Motorcycles, Super, Sports and OPenwheel are done as of this update.
			  Fixed strAdvancedFlags on the Open-wheel class and doubled their down-force.
			  
1.9.1 - 1.9.7 internal, Discombobulate https://www.youtube.com/watch?v=B62ACxuq8Pw read below or above depending where applicable
			  
1.9.8 Update, HEY i'm back! Continuing with the previous patch.. the Drag coefficient issues where sorted out and retested, created a few more sleepers.
			  Fixed the Stafford, accidentally had the top speed of 1 in the meta. Lowered the downforce on the 900R, again fat finger typo.
			  Slightly lowered "fTractionCurveMin/MaX" on a few Los Santos cars to make them less snappy (-0.3 in all cases)
			  Dubsta2 is now 100% more BRABUS, Cyclone is now 100% more Rimac, Neon is 100% more Taycan Turbo S, 
			  all the overlooked sleepers now have the new sleeper formula applied, Lift kits applied where deemed stylish,
			  Lowered "fTractionCurveMax" on the Trophy trucks by -0.3, Coquette D10 was given the Z07 treatment, 
			  Unlocked the secrets of Diesel inertia, Fixed the floatyness on the Police Taurus, Fixed overlooked drive bias balances in drift versions
			  and I believe that's it for now, see you next time!
			  
1.9.8 Hotfix, Fixed an oversight in the SP Drift version, not all the vehicles where set to RR and OIV installers created.

1.9.8.1 Update, Jackal was revisited, Comet S2 was given GTS RS treatment, a sleeper was created, New Contract Vehicles where added and tuned accordingly
				Manual and OIV installers are now both included in Single player folder 
				
1.9.8.2 Hotfix, Forgot to include updated carcol/variation metas for FiveM and set vehicles to FR in Drift versions, minor drag coefficient changes.
			  
1.9.8.3 Hotfix, Petrol tank upgrades for certain vehicles. Reever didn't have a 6 speed, minor adjustments to the Coquette D10, Comet Retro Custom and Zeno suspension flags, Sugoi and Prairie were lowered and suspension adjusted to handle being lowered, also Prairie was slightly detuned but upgraded to a six speed (¬‿¬). 

1.9.8.8 Update, Furore GT upper suspension limit adjusted, Sugoi revisited, Hotring adjusted, Comet SR advanced flags change to handle added down-force, V-STR was upgraded to a Blackwing, "EnHanCeD & eXpAnDed" vehicles added but do not work. Sleepers where Created. Criminal Enterprises tuned and added.

1.9.9 Update, SM722 was lowered slightly, Tyrant is now 100% more Regera, Drug Wars cars added, Missing meta data adeed to FiveM metas.

1.9.9.1 Update, Tyrant overspeed fixed, Buffalo STX brake light fixed(FiveM Only), Project is now hosted on GitHub

1.9.9.2 Update, San Andreas Mercenaries vehicles added and tuned appropriately, various handling flag changes, minor adjustment to Everon

2.0 Upgraded, Latest DLCs added, overhauled the overhaul, Fixed Bufflo lighting bug again (FiveM Only), minus the motorcycles and quads for now.
