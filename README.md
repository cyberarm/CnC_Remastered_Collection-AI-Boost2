# AI-Boost for Red Alert
Last update at: 3 may 2022

Please follow the steps below to update and reactivate the mod:
- Disable the mod in the Mods Menu
- Unsubscribe from the mod in the in-game Workshop Mods menu
- Quit and restart the game
- Re-subscribe to the mod via the Workshop Mods menu
- Activate the mod and restart the game as prompted
- The updated mod should then work as intended

News:
- Added more infos about how AIBoost work (to avoid confusion)
- The AI Chronotanks no longer jump in groups. Human is unable to do this, so it was unfair. You can re-enable group-jumps by the .ini file if you like
- AIBoostLevel is dynamic by the number of enemies/friendlies he personally sees, to rebalance unfair groups (Can be enabled/disabled/tweaked using the .ini file.)
- You can now set the boost for your allies and your ennemies independently (when dynamic AI boost is disabled)
- Free-For-All detection, it automatically disables Dynamic AI in these cases because there are no teams so nothing to rebalance
- A lot of tweaks which greatly increases the AI intelligence (See new options in the .ini file also)
- Now the AI technology levels-up more faster
- AI build more air units/defenses and GAP generators
- Selling buildings to restore power or cash is smarter now
 
Hotfix:
- Sometimes harvesters could go to the other side of the map instead of going to the nearest Tiberium field. It's fixed now (Thanks to Cyberarm)
- AI ship production was unlimited. An AI try to build more ships than all other enemies combined, resulting in unlimited production. Now it counts the human ships only. In the .ini file you can edit some settings for this
- AI building production was unlimited when having multiple enemies. Now it calculates the average buildings of all enemies and use this as baseline
- AI keeps building harvesters in some situations. Now you can set a max limit in the .ini file
- Fixed AI make too much engineers
- Fixed the AIAttackFirstTime (in the .ini), now it works!
- GAP selling loop is fixed
- Fixed the calculation of certain building limits when AI steal technology

--- 

General Mod info:
- The Rampastring Quality of Live MOD. (waypoints, etc.)
- Engineer instant capture
- Engineers automatically choose new target after capturing
- Additional Zoom Levels
- RA Immersive Helis Mod (And all Air units have a sight) (Use 'L' to land)
- Tech stealing by capturing a building with an Engineer (Allies vs Soviets)
- Harvester have memory of latest harvest location, this is now editable by .ini file
- AI knows how to use Thiefs and Spies
- AI knows how to use a MAD Tank and Demo truck.
- AI knows how to use chronoshifting with a Chrono Tank
- AI knows how to use Naval stuff
- AI attacks interval uses different ways (Hunt, Closest enemy, etc.)
- AI Scatters all units on new attack launch to unlock stuck/blocked units
- AI Air units no longer just attack Refineries, it selects random between basedefence, factories, power, buildings, naval units or all threats
- AI understands importants of buildings & units a lot better and uses it during attack
- AI Engineers no longer walk in groups. They choose his own targets
- AI Customizable limits for number of AI buildings, tanks, etc.
- AI handles his cash flow and building priorities/limits a lot smarter
- AI doesn't wait for the player to let his base grow and/or tech up to the highest level
- AI's MCV goes to tiberium and deploys there for extra base, AI limitations for buildings, etc. will grow on each MCV deployment
- AI scans for human Naval objects, if he detects a Naval stuff, it will upscale his Naval and Air stuff
- AI lowers tank production if human goes naval and GroundWar is disabled (Allies still build Chronotanks beacause they can Chronoshift)
- AI Medics and Mechanics now only repairs friendly units
- Sight range of the MCV is increased, this was needed to get the AI to find a deploy spot
- ChronoKillCargo set to False. Chronoshifting APCs or transports will not kill any passengers or cargo
- Aftermath fast build MOD (Use .ini to enable/disable)
- AttackMove MOD (Use Shift)
- Now its possible to add more starting cash and units! Editable by the .ini file
- You can now remove toggle with space between old/new graphic in gameconstant.xml
- Added the option to remove shroud from the map
- AI have a limit of contruction yard/war factory/vessel carrier according to fast build on/off. It's more realist against a humain even with a massive base

The AI monitors what you are doing and uses this on how to react while upgrading his base. More Factories, Air stuff, Air defence, Naval stuff or Refineries if you have created more of this. It's totally dynamic. :-)

---

Note:
- The more Tiberium is available on the map, the harder it is to beat the AI. You might need a faster pc because of the amount of units etc.  :-)
- AI Boost level and almost all other setttings are editable using the .ini file. It's located in: C:\Program Files (x86)\Steam\steamapps\workshop\content\1213210\2221741447\AIBoost\CCDATA\AIBOOST.INI

---

To do / whishes:
- AI Minelayer control
- AI Chronosphere control in Skirmish
- AI Iron Curton control in Skirmish

Known issues:
- Tech stealing: The human player has to re-deploy the Construction Yard to MCV and back to unlock all stolen tech. Also for the War Factory. (Or you have to build a extra one) It also changes the voices for some countries. Currently, we don't know how to correct this

Source code:
https://github.com/Bast75/CnC_Remastered_Collection-AI-Boost2


Greetings, have fun and don't forget to rate this mod
Bast75

