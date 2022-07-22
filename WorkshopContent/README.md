# AI-Boost 2.5 for Red Alert
Last update at: 22th July 2022

Please follow the steps below to update and reactivate the mod:
- Disable the mod in the mods Menu
- Unsubscribe from the mod in the in-game Workshop mods menu
- Quit and restart the game
- Re-subscribe to the mod via the Workshop mods menu
- Activate the mod and restart the game as prompted
- The updated mod should then work as intended

--- 

Latest changes:
New:
- Harvester prio switcher. There is a 5% change of AI goes wild on harvester hunting. The rest of the time it gives harvesters lower prio
- Added an option to allow the AI to make extra base using MCV's (Will use chronoshift or vessel transport for map with islands)
- AI generates a team to proctect MCVs while going to extra base location
- AI knows how to use Chronosphere and Iron Curtain
- Harvester memory option re-added and made editable by .ini file
- Added new slowdown production for the AI to compensate the multiple production hack. Time to build is like human now. That allow to increase war/yard/barrack/vessel limit a lot
- Building limit for AI is increased by x2 when last construction yard is built or captured

Fixed/Changed/Improved:
- Prio for Tesla & Power buildings improved
- Fixed the way AI count the refineries and the vessel units. He count according to the enemies average instead of human (because in multiplayer, you can have more than 1 human)
- Several AI-tweaks for Naval War and Mixed War
- Several AI-tweaks for Air and Anti-Air production
- Fixed some performance issues
- Good pathfinding is back
- Selling loop for cash is fixed. Now AI only sell when tiberium is low on the map, when no more harvester and cash drop drastically

---

Included mod's:
- CFE Patch Redux 1.8 mod(Veterancy mod(default disabled), vanilla/multiplayer/performance fix)
- The Rampastring Quality of Live mod
- Engineer instant capture
- Additional Zoom Levels+++
- RA Immersive Heli's mod (And all Air units have a sight) (Use 'L' to land)
- Attack-Move mod (Use Shift)
- Aftermath fast build mod (Use .ini to enable/disable, default disabled)
- ChronoKillCargo set to False. Chronoshifting APCs or transports will not kill any passengers or cargo
- Added the option to remove shroud from the map

Own mod's:
- Added some performance features, the game runs smoother now
- Tech stealing by capturing a building with an Engineer (Allies vs Soviets)
- Sight range of the MCV is increased, this was needed to get the AI to find a deploy spot
- Now it's possible to add more starting cash and units! Editable by the .ini file
- You can now remove toggle with space between old/new graphic in gameconstant.xml
- Added extra zoom levels to the mod: "Additional Zoom Levels"

AI changes:
- AI handles his cash flow and building priorities/limits a lot smarter
- AI customizable limits for number of AI buildings, tanks, etc. using the .ini file
- AI scatters all units on new attack launch to unlock stuck/blocked units
- AI understands importance of buildings & units a lot better and uses it during attack
- AI attacks interval uses different ways (Hunt, Closest enemy, etc.)
- AI Harvester prio switcher. There is a 5% change of AI goes wild on harvester hunting. The rest of the time it gives harvesters lower prio
- AI Air units no longer just attack Refineries, it selects random between base-defense, factories, power, buildings, naval units or all threats
- AI knows how to use Thief's, Spies, MAD Tanks, Demo truck and chrono shifting with a Chrono Tank
- AI knows how to use Naval stuff
- AI Naval war detection. The AI scans for human Naval objects, if he detects Naval stuff, it will upscale his Naval and Air limits
- AI lowers tank production if human goes naval and doesn't produce a lot of tanks (Still builds Chronotanks because they can Chronoshift)
- AI Engineers automatically choose new target after capturing or loosing focus on previous selected target
- AI Engineers no longer walk in groups. They choose their own targets
- AI Medics and Mechanics now only repair friendly units, not enemy units
- AI doesn't wait for the player to let his base grow and/or tech up to the highest level (Radar, Air units, etc.)
- AI build MCV's and deploys them, AI limitations for buildings, etc
- AI have a limit of construction yard/war factory/vessel carrier according to fast build on/off. It's more realist against a human even with a massive base
- AI monitors what you are doing and uses this on how to react while upgrading / expanding his base. If you have more of building x, he builds more of x too. It's totally dynamic. :-)
- AIBoostLevel is dynamic by the number of enemies/friendlies he personally sees, to re-balance unfair groups (Can be enabled/disabled/tweaked using the .ini file.)
- You can now set the boost for your allies and your enemies independently (when dynamic AI boost is disabled)
- Free-For-All detection, it automatically disables Dynamic AI in these cases because there are no teams so nothing to re-balance

---

Note:
- The more Tiberium is available on the map, the harder it is to beat the AI. You might need a faster PC because of the number of units etc.  :-)
- AI Boost level and almost all other settings are editable using the .ini file. It's located in: C:\Program Files (x86)\Steam\steamapps\workshop\content\1213210\2221741447\AIBoost\CCDATA\AIBOOST.INI

---

To do / wishes:
- AI Minelayer control in Skirmish
- AI Chronosphere control in Skirmish
- AI Iron Curtain control in Skirmish
- In skirmish add new play-methods for the AI like: Turtle, Air rush, Infantry rush, Tank rush, etc.
- In skirmish and not in FFA-games, the AI should be enabled to ally or declare war to change his friends and enemies
- The AI should know how to send a MCV (Or other unit) into a transport and send it over water to a better location
- Like in RA2 Yuri's Revenge: Units should be able to scan the area and attack a specified object while avoiding all other dangers. (Attack object from other side by driving around units and defenses)

Known issues:
- Tech stealing:
The human player must re-deploy the Construction Yard to MCV and back to unlock all stolen tech. Also, for the War Factory. (Or you must build an extra one)
It also changes the voices for some countries. Currently, we don't know how to correct this

Source code: (If you know how to program C++, we always can use some help with our To-do's and wishes)
https://github.com/Bast75/CnC_Remastered_Collection-AI-Boost2


Greetings, have fun and don't forget to rate this mod
Bast75
xXMini FrankiXx
