# DaC V6 Changelog

![](https://i.imgur.com/bgYdoLw.png)

25rd February 2025
- Update EOP to latest nightly
  
23rd February 2025
- (Karl) Fixed Beacon of Hope mercenary pools not replenishing
- (Karl) Corrected number of defenders from garrison building in Alcfud if held by a wildmen faction
- (Karl) Sauron now spawns after 5 ring rotations instead of after 8 (around turn 130)

19th February 2025
- (Reeveli) New greater resolution banners for ND standard bearer, three variants
- (Reeveli) Also Gondor and DA texture variants for above
- (Karl) Added Silvan Marchwardens to the Anduin Vale waystation
- (Karl) Added Hîtherbin to the Lothlorien waystation
- (Karl) Added Arthírochon to the Woodland Realm waystation
- (Karl) Added Hin-e-Daur to the Woodland Realm waystation
- (Karl) Added Mordag Fishermen to the Enedwaith waystation
- (Karl) Added Snow Trolls to the Angmar waystation

16th February 2025
- (Reeveli) New images to replace old live action ones for the following event chains: Aragorn, Gandalf & Army of the Dead
- (Reeveli) Added some more images for Ered Luin Ring script as there were many shared previously

7th February 2025
- (Karl) Adjusted behaviour of starting Noldor barracks in Imladris for player High Elves to allow immediate recruitment of Amanyar
- (Reeveli) Event images cleanup:
    - All unique events should now reside in southern_european folder to keep things consolidated. I expect this to be an ongoing process
    - Removed 126 duplicate images from various cultural folders
    - Moved 276 currently un-referenced (not in historic_events or Lua scripts) events away from working space to a new archival folder in  - data\ui\archive_eventpics
    - Added reverse-engineered EL and Blue Wizards event image frames that I've used to southern_european folder where other templates also reside (search for TEMPLATE)
- (Reeveli) Added some more images for Ered Luin Ring script as there were many shared previously

21st January-29th January 2025
- (Reeveli) New portraits for Moria starting generals
- (Reeveli) New portrait for Moria leader in campaign selection
- (Reeveli) New portrait for Drangu, Angmar's Orc general
- (Reeveli) Moved some obvious Uruk portraits out of generic Orc pool to Isengard
- (Reeveli) Updated Dol Guldur green book image and text
- (Medik) Renamed Privateer Axemen/Cavalry to Vagabond Axemen/Cavalry and rewrote their description

15-20th January 2024
- (Reeveli) Fixed Isengard Orthanc Wardens not having their accent defined
- (Reeveli) Enabled Snow-Trolls in custom battles for Angmar
- (Reeveli) Added Gondor and Dol Amroth banner texture variants for ND standard bearer
- (Medik) Restore some faction intros, victory videos and add a generic win video
- (Medik) Remove unnecessary united references everywhere except bmdb
- (Reeveli) Added new images for Ered Luin relic reclamation events
- (Medik) Added eventpics for all Dale events with consistent frames and art style

8th January 2024
- (Medik) Removed some AI cheats coming from traits for all generals (to compensate for incoming AI improvements)
- (Medik) Added Sharku as a custom general and a custom event for his spawn
- (Medik) Added Elven Union colour and name change

6th January 2024
- (Reeveli) Gave Lurtz semi-unique BG. Buffed version of Uruk Archers with custom unit voices.
- (Reeveli) Buffed Sauron's spawn army to be fit for a Dark Lord.

2nd January 2024
- (Medik) Remove Command effects/traits from Bilbo/Barliman and gave them more appropriate governing/lore traits instead
- (Medik) Gave Andy Greenway Cavalry to compensate

25th December 2024
- (Medik) A small portion of Bree's population moves to Mengelen after the Barrows have been cleansed
- (Medik) Characters afflicted with the "Cursed Blade of Westernesse" can now go to Imladris to be healed

24th December 2024
- (Lerynian) Added new custom csm for lake town general
- (Coma) Updated Rhun Unit Cards and Baruun unit cards

22nd December 2024
- (Coma) Updated remaining dale and Rhovanion Merc cards 
- (Coma) Updated Erebor Unit Cards
- (Coma) Updated Ered Luin unit cards
- (Coma) Updated Khazad-dum unit cards
- (Coma) Updated Khand Ancillary Cards
- (Coma) Changed Arkish Custom portrait

15th December 2024
- (Coma) Updated Dol Guldur Unit Cards and Unit info cards
- (Medik) Give Moria Snaga Stalker recruitment from mines and better bonuses overall
- (Medik) Nerf Ithilien Rangers accuracy

14th December 2024
- (Medik) Unit effects are now automatically generated with Lua meaning they will always be 100% accurate and you no longer have to run the unit stats tool when editing stats/adding new units
- (Medik) Nerfed the size, attack and defense of Farmhand Pikemen

12th December 2024
- (Lerynian) Updated all Dale unit descriptions with those made by MVKing
- (Karl) 
	- Added two landmarks made by Reeveli, one in Edoras and one in Framsburg (thanks!) and changed necessary files
	- Re-ran bmdb script as Rohan was missed previously
	- Fixed waystation for Khand so they can no longer recruit Great Beasts or Temple units with 8 turn replenishment
	- Fixed waystation for Rohan so they can no longer recruit AOR units outside intended settlements

9th December 2024
- (Medik) Consolidated (after many painstaking hours) and cleaned up 500mb from the `data/ui/units` and `data/ui/unit_info` folders such that **ONLY** faction variants need to go in their respective faction folders. The **mercs** and **merc** folders respectively are now the default directories. 
		This in effect, combined with the BMDB changes to give ownership of all units, should essentially allow any faction to recruit any unit without any additional changes

8th December 2024
- (Coma) Updated most of the mainline ND infantry unit cards, Fixed Dale cards and Mordag Fishermen card

5th December 2024
- (Medik) Allies settlements are now always revealed to you on the campaign map

3rd December 2024
- (Medik) Updated rebel faction symbols and assigned them properly to the correct cultures

1st December 2024
- (Medik) Added custom Angmar UI (modified version of Mordor's)
- (Medik) Allow Dale to hold tournaments from highest stable tier or after refitting the Palace
- (Medik) Northern Dunedain, Arnor and the Reunited Kingdom now have a 
	- Unique name
	- Unique banner symbol
	- Unique primary and secondary colours
	- Unique faction symbol
	- Unique diplomacy symbol

	Thank you kvintus for the Arnor faction icon

28th November 2024
- (Medik) Added new script for Angmar
	- Conquer historic Arnorian settlements to recieve reinforcements from Sauron in the form of custom generals and units
- (Medik) Removed Barrow Wights from T2 and T3 culture buildings
- (Medik) Added a new "Corrupted Barrows" building, unique to Angmar
	- Only constructable in regions with Barrows
	- Enables the recruitment of Barrow Wights

27th November 2024
- (Medik) Added new script for Dale revolving around the recovery of the Master's stolen treasure
- (Medik) Added a description for the Ruins of Lake-town building
- (Medik) Added 7 new landmark buildings in Harad and Umbar. Thank you Skywalker for the research, building ideas and descriptions!
	- Catacombs of Furinor 
	- Path of the Benevolent
	- Temple of Sauron
	- Basilica of Númenor
	- Muhad Bazzar
	- Mumakil Graveyard
	- Dark Brothers Landing
- (Medik) Updated most Harad unit descriptions (Thank you Skywalker!)
- (Medik) Gave Serpent units +2 armour
- (Medik) Added 1 new Landmark building for Gondor (Thank you Reveeli!)
	- Houses of the Dead in Minas Tirith
- (Medik) Added 3 new Landmark building for Erebor/KD (Thank you Reveeli!)
	- Doors of Durin/Hollin Gate in KD West
	- Durin's Tower in KD West
	- Tomb of Thorin II in Erebor

24th November 2024
- (Karl) Re-done recruit_priority_offset for all recruitable units in hopes of improving AI economy and army compositions.
- (Karl) Updated all traits/ancillary descriptions with the BattleSurgery effect to accurately represent thecasualties recovered bonus.
- (Karl) All traits/ancillaries with effect level over BattleSurgery 10 has had effect level reduced to 10.
- (Karl) Reduced hidden AI trait levels on BattleSurgery from 10 and 20, to 4 and 8 respectively.
- (Karl) Replaces Snow Trolls with Trolls in Morva Tarth for Angmar and moved requirement down to Town-tier settlement
- (Karl) Added Snow Trolls to Angmar Tier 3 barracks in Carn Dûm and Litash
- (Karl) Added Orthanc Sentries and Orthanc Wardens to Isengard T3 barracks in Hornburg
- (Karl) Adjusted AI Snow Troll replenishment in Carn Dûm

19th November 2024
- (Medik) Fix faction victory videos/fmvs not playing correctly
- (Medik) Fix ND wrong starting event pic
- (Medik) Fix double Far-Rhun Merc recruitment in some provinces

17th November 2024
- (Medik) Added stack auto-sorting script
- (Medik) Added Python script for automatically generating the UI and text entries for a building
- (Medik) Added system for setting settlement strategy models based on a wide variety of criteria including buildings
- (Medik) Added Ruined Lake-town cas model

16th November 2024
- (Lerynian) Added new strat models for Dale: King, General, Captain, Diplomat and Spy
- (Medik) Added custom "War Declared" event pics for all cultures
- (Medik) Changed capital change cost to 5,000

11th November 2024
- (Medik) Upgraded EOP to V4
	- Includes overhauled campaign AI written in-engine (Credits to Fynn)
	- Integrated Freecam support
	- Overhauled and much easier to use Lua scripting system
	- Vanilla bug fixes such as Trade Wharfs working correctly with the Steam version of the game
	- Ability to remove all traces of Khaki/Grey text making UI overable much much easier to read
	- Removed limit on number of buildings
- (Medik) Rewrote a little bit of the Dale script in V4 syntax
- (Medik) Disabled "Unique Names" script by Wicked until I figure out why it's crashing

2nd November 2024
- (Lerynian) Added all unit descriptions for Dale(still need to be reworked).
- (Lerynian) Replaced Northman CSM with Khand CSM for Logath settlements

4th October 2024
- Added first part of Dale Mission 2
	- If Dale is player, Erebor gets Withered Heath in auto expansion instead of the Logath regions
	- If Dale or Rhun owns 3/4 Logath settlements, they can recruit them from their stables

4th October 2024
- (Medik) Refactor and tidy up Lua scripts
- (Medik) Added support for EOP units

3rd October 2024
- (Medik) Gave Ugluk upgraded Uruk-hai Infantry instead of Berserkers
- (Medik) Made the following adjustments to walls, towers and gatehouses
	- Made all projectiles fired from towers and gatehouses "fiery" to allow players to more easily distinguish where they are being shot from
	- Reduced fire rates of most tower and gatehouse projectiles, especially ballistas
	- Reduced health of walls, towers and gatehouses
	- Normalized control radious for towers
	- Made wooden walls, gatehouses and towers easier to set on fire
	- Changed "Extra wall defences" to "Improved tower defences"
	- Ballista now only come from stone walls
- (Medik) Gave every faction ownership of every unit in the BMDB, effectively removing silver surfers forever. Thanks to Fynn for his script and the Modding Tool.
- (Medik) Buffed Uruk-hai Bodyguard to not be so similar statwise to Uruk-Hai Infantry

24th September 2024
- (Medik) Disabled night battles for AI

21st September 2024
- (Medik) Added Asseaux's updated event strings for Goblins and Elves
- (Medik) Gave Bregost Level 1 farms instead of a fishery
- (Medik) Added potentially fixed version of Fornost with better pathfinding (Thanks to Annatar!)
- (Medik) Adjust AI value of Siege to try and reduce late game siege spam

6th September 2024
- (Medik) Add Lua launch w/debug Visual Studio Code configurations
- (Medik) Gave Bregost a starting Fishery
- (Medik) Slightly buff Udege Marine bomb to make it more impactful
- (Medik) Added Asseaux's updated Gondor event strings

28th August 2024
- (Medik) Gave Bregost a starting Fishery

25th August 2024
- (Medik) Added a script to create a zip file of changed files given two Git commit hashes. See the README.md for more details.
- (Medik) Gave Ghan-Bhuri-Ghan the Druedain Statue ancillary

24th August 2024
- (Medik) Add UI and descriptions for the Dalian Barracks and Dalian Stables building lines
- (Medik) Fixed floating spiders
- (Medik) Made the following changes to how AI calculates the value of certain units in all scenarios. For example, in battle, when it says 'Victory seems certain', when units are engaging each other, when it decides which units to recruit, to evaluate army strength for attack decisions, for auto resolve balance and results etc. The long term goal director also uses this for the values you have in campaign_ai_db like military balance and free strength balance.
  - Heavy Cavalry: 30%
  - Light Cavalry: 25%
  - Missile Cavalry: 20%

23rd August 2024
- (Medik) Added AA's Naru n'Aru to the T3 Barracks and kept them only in historical Numenorean locations - Thanks Karl!
- (Medik) Fixed a bunch of random syntax errors in the EDB - Thanks Karl!
- (Medik) Fixed all the latest typos in dac_bugs_typographical
- (Medik) Updated EOP to version 3.3.0: 
    - https://github.com/youneuoy/M2TWEOP-library/releases/tag/M2TWEOP-3.3.0
	- This enables the following exciting features
    	- Culture limit is removed
    	- Abiltiy to use EOP units in any in-game file (EDU, EDB, descr_strat etc.)
    	- Armies with elephants class units will properly attack settlements during battle now
    	- A bunch of Lua additions, too numerous to mention here
    	- This update is not save-game compatitble
  	- This version introduces a few bugs, which I will try to fix in EOP by creating a 3.3.1 version with just the bugfixes (EOP has advanced far past this release now but version 4.0.0 contains many breaking changes and I don't want to disrupt Wicked's work)
- (Medik) Update EOP to 3.1.1 to fix bug with Green Books
- (Medik) Added UI for brothel, inn and farms to middle_eastern folder as they were using vanilla but weren't present in the mod folder causing issues
- (Karl) Combat_V_X related traits now have effect descriptions
- (Medik) Fixed floating wargs
- (Medik) Repacked animations and updated descr_skeleton using IWTE
  -  ALL files you need to work with are in `data/animations` and in `data/descr_skeleton.txt`
  -  Please see the README file for how to work with animations in DaC going forward. It should now be much much easier as you don't ever need to have certain animations in your `Medieval II/mods` folder, only in your `Medieval II/mods/dac-beta` folder. 
  -  DO NOT use tools like Modellers Toolbox. Use IWTE and descr_skeleton.txt ONLY.
- (Medik) Fix Lorien missing diplomacy lines
- (Medik) Fix dale large cities crashing
- (Medik) Updated the "Ethring Revenge" army to consist more of Fiefdom units and less of traditional Gondor mainline units
- (Medik) Spawn a custom "Dragons Wrath Guildsmen" general for Rhun when when they complete the Artifact quest

22nd August 2024
- (Medik) Removed all references to the "thiefs_guild" which does not exist and was causing guilds to be extremely buggy and non-sensical - Special thanks to Dioarchet for this excellent find!
- (Medik) Fixed Dwarf Garrisons not creating the correct amount of units
- (Medik) Fixed Chief of Shire ancill not being able to trigger at all
- (Medik) Deleted all lookup and enums files that are obsolete
- (Medik) Fixed Minas Ithil Guardians not being available in the Waystation
- (Medik) Fixed wrong UI for Middle-Eastern Fighters Guild
- (Medik) Fixed Boromir's speech firing when Osgiliath East is lost (Thanks Racer, you're a legend!)
- (Medik) Fixed incorrect Waystation description for Ar-Adunaim
- (Medik) Fixed Freca losing his hero ability when he gets his bodyguard upgrade
- (Medik) Added a new unique building "The Brown Boat" to Tusturë

2nd August 2024
- (Lery) Added new horse for Dunland, EW and Beorning Riders to match thier wildness :D 

26th June 2024
- (Medik) Updated Hawin and Forthwin's biography to better match their family tree and be more interesting - Many thanks to zayzo for the text
- (Medik) Reduced availability of Great Beasts and slightly increased availability of Olog-Hai and Temple Knights, Wards and Marksmen to compensate

6th June 2024
- (Medik) Added 42 custom Isengard portraits and updated the Ugkluk custom portrait - Many thanks to Fog Lurker for the portraits

24th May 2024
- (Medik) Added gold versions of vanilla cursors to better match the DaC theme

16th May 2024
- (Medik) Fixed misconception about modders in shared.txt

13th May 2024
- (Medik) Replaced vanilla plague event text and event image - Thanks Johan!
- (Medik) Added proper mechanic descriptions for agents
- (Medik) Added bullet pointed lists for building/unit abilities

12th May 2024
- (W) Increased charge distance for Logath Elders (5 --> 45) and Swifts (8 --> 30) to make their charge work properly

6th May 2024
- (Medik) Added "Ring script" select outlines for characters and settlements
- (Medik) Added 50+ missing .tga.dds textures in models_strat/textures
- (Medik) Converted all .tga files in models_strat/textures to zero byte files (They are never read anyways if the .dds files are present). Saved around ~300mb of memory.

4th May 2024
- (Medik) Added Louis Lux's new Legolas Campaign and Strategy models
- (Medik) Fixed Warg Pack sprite
- (W) New UI for Northmen dirt paths, roads and great roads. For now, Dale have access to great roads, however, those will be script locked later on.

3rd May 2024
- (Medik) Added Medik's Ambient Sound Overhaul
- (W) The game now detects the player's mod folder name, so your mod folder can now have a different name from "Divide and Conquer". (only relevant for the beta)
- (W) New UI for Northmen farm buildings.

2nd May 2024
- (Medik) Added Louis Lux's new Istari models
	- New battle and strat model for Gandalf the Grey
	- New battle and strat model for Saruman the White
	- New strat model for Radagast

7th April 2024
- (Coma) Updated most Dale unit cards & Unit_info cards

31st March 2024
- (W) Removed spear_bonus_4 and spear attributes from Gate Keepers to get them in line with other halberd units.

3rd March 2024

- (Lery) Uploaded new armour upgrade for Dunedain Wardens and gave +1 armour to match them with rangers armour stat. Also changed the "hide_anywhere" to "hide_improved_forest" to match the last upgrade visuals.
- (Lery) Uploaded new and now for sure last unit for Dale roster. A unique unit you would get upon completing script.

2nd March 2024 
- (W) Brand now starts married, so his marriage popup does not interfere with the camera panning for Dale's first mission.

21th February 2024 
- (W) Fixed some typos

12th February 2024 
- (W) Fixed some typos

11th February 2024 
- (L) Isengard culture building UIs have been sharpened
- (L) The small UIs for Dorwinion's gardens have been sharpened
- (L) Updated Orthanc temple UIs with higher quality versions
- (W) Fixed a defective label for Avl'yn in campaign_script
- (W) Fixed an error with Dunland's temples which required the destruction of the pre-built T1s for Dunland and Enedwaith
- (W) Implemented relentless animations for 1h Dwarven Mace/Axe and 2h Dwarven Hammer/Mace/Axe attacks
- (W) Balin and his bodyguard are now relentless
- (W) Added relentless to Dwarven generals

10th February 2024
- (L) Added flavour text and UIs for the remaining new temples 
- (L) Dunland's starting temple has been downgraded and Rhun's upgraded for flavour 
- (L) Faction info scrolls (including SA scrolls) have been updated with blurbs for the new religions 
- (L) Added mentions of Saruman's mills to a few Dunland events 
- (L) Dunland's faction info scroll will updated to Gwathuirim if you backstab Saruman 
- (L) The new religions should now be 100% done!!! 

4th February 2024
- (Coma)Implemented new Mordag unit models
- (Coma) Updated unit and unit_info cards for the Faolan and Mordag units

3rd February 2024
- (W) Added labels to some characters in descr_strat and campaign_script in preparation for the Unique Names script.
- (W) Implemented the Unique Names script. It makes sure unique character names are actually unique by renaming the doppelgangers. No more spies called "The Witch-king" or captains named "Captain Gandalf" etc.

27th January 2024
- (W) Nazgul for player Mordor and player Isengard should now be able to get traits and ancillaries, including the ring
- (W) Gave Shi'vuus his Nazgul Robes
- (W) AI horde factions will now be killed off once they lose their last settlement (did a couple of successful attempts, but more tests are needed)

25th January 2024
- (L) Incorporated numerous minor fixes for the export_descr_ancillaries, export_descr_character_traits, descr_strat and export_descr_buildings files thanks to b0Gia

23rd January 2024
- (W) Replaced all instances of NavalCommand with Command as the former was broken. Admirals should now also display the correct number of stars on the pre-battle screen. 

21st January 2024
- (W) Created a new mount for Rohan BG and Royal Guard (old looks but faster horse animation) since they were slow as molasses.

20th January 2024
- (W) Removed Rhun's access to T3 sea trade (docklands) as it requires a T3 port which they cannot build
- (W) Removed Squalor from the kind/benevolent ruler traits as it made no sense
- (W) Dale's victory conditions do not include Rhun anymore (required for the new script)
- (W) All T2 garrison buildings now provide 3 upgraded and experienced units(5 instances of 2 units fixed)

13th January 2024
- (W) Gave a slight buff to Wardens of the White Tower (now 12/30) and a slight nerf to Talon Knights (now 11/28) to account for the fact that WotWT are supposed to be the best of the best in all of Gondor
- (W) Gave Darkblades +20m range and the ranger projectile since they are supposed to be counters to the Dunedain rangers

9th January 2024 
- (L) The Golden Lady has been intergrated (aka Lothlorien now gets Galadriel has their faction leader)
- (L) Galadriel starts locked to Lothlorien for the player and can be unlocked when DG is conquered or if Celeborn perishes. For the AI, she is moved to the wasteland and will only take the field as part of Lothlorien's last stand army
- (L) To avoid technical weirdness, Lothlorien will be destroyed if Galadriel perishes so don't get her killed.... She does not yet have a custom BG (this is planned)
- (L) Mercenaries are now standardized so if you are able to recruit a merc, you'll be able to train it in all eligible regions- previously there were a few cases where certain factions could only train certain mercs in a subset of the full regions they came from.
- (L) At long last mercenaries have been updated for the new cultures. Generally speaking availability remains the same, with the following exceptions: Followers of Melkor (aka Melkor's Shadow) can no longer recruit any human mercs (since they are wholly orcish nations), and Followers of Saruman can now recruit virtually every human merc (this represents the Voice of Saruman and Saruman's established influence among human bandits and spies).
- (L) Among other minor tweaks includes the fact that Dorwinion now has access to elven and Far Rhun mercs, and Khand now gets access to Dwarven mercs. Have fun!
- (L) Shrines of Melkor now have descriptions and UIs

4th January 2024
- (W) Changed availability for Dalian Barracks and Stables in castle settlements from Castle-Stronghold-Fortress to Keep-Castle-Stronghold

1St January 2024
- (W) Fixed some typos

31st December 2023
- (W) Updated our EOP setup to v3.0.1
- (W) Implemented the prologue and the first mission of the new Dale script

17th December 2023
- (W) Removed all castle versions of culture buildings from the edb. Also changed respective descr_strat and campaign_script entries. Freed up 16 more building slots to give us a little more leeway.

10th December 2023
- (W) Buffed the defense stat of Orc Avengers. Makes no sense that your most elite unit has the lowest defense stat in all your roster. 
- (W) Put the bonuses provided by culture buildings in order.

9th December 2023
- (W) Set up the new Dale start (player starts with Dale only, AI stays the same) 

3 December 2023
- (Lery) Lake-town Custodians are now available as alternate generals in Esgaroth

2nd December 2023
- (Lery) Lake-town Guildsmen again available(not sure why but got deleted last update). Also new and last armour upgrade for Regular Dalian swordsmen and longbowmen.
- (Lery) Some changes to Dale units in EDU like stats or costs. Deleted unnecessary armour upgrades.
- (Lery) Added new unique buildings for Dale recruitment(no UI and text yet). 2 new buildings: Dalian barracks and Dalian stables, all having 3 tiers(they are not restrickted by scripts yet for the purpose of testing).   Lake-town units will be recruited from some eco buildings. Lake-town Custodians are not available to recruit as of now(they need scripts). Can't help much further since I am too stupid, so this concludes my work on Dale for next version. Nothing new will be added other than visual bug fixes.

22nd November 2023 
- (W) Implemented sprites for all Dale units

20th November 2023 
- (W) Fixed a small bug with the Gondor and Bree radar_map_background files

18th November 2023 
- (L) Updated some of the Orthanc Warden's voice lines so they are now correct
- (W) Fixed many typos and spelling inconsistencies in export_buildings.txt
- (Lery) Updated the shield on Laketown mariners. Added an visual armour upgrade for Laketown Vaultguard. Added new bannerscarriers and officers for all Dale units.
- (Lery) Changed the faction banners partially (more if I get lust to it).
- (Lery) As per suggestion increased the bodyguard unit size for Mordor, Goblins and Dol Guldur to balance their poorer stats. Available now cause of EOP unit replenishment cap is no more.

13th November 2023 
- (L) Renamed the Orthanc Guard to Orthanc Sentries
- (L) Updated many of Dunland's units with new voice acting courtesy of Verrix (these include Heralds of the Twofold King, the Orthanc Wardens and Sentries, the Warband units and the Frekkalingir units)

12th November 2023
- (W) Fixed hundreds of typos and spelling inconsistencies in historic_events.txt

11th November 2023
- (W) Fixed some typos
- (W) Added Troll-men Champions to Harad's waystation

7th November 2023

- (W) Arulad general now spawns with Arulad Dragonriders, as intended
- (W) Removed the forced declaration of war between Gobbos and Anduin on turn 25 for player Gobbos
- (W) Fixed the Trollmaster trait to not exclude eastern_european, the only culture that can actually get it

5th November 2023

- (W) Restructured our EOP setup (youneuoy_Data/plugins/lua) - NOTE: starting point of everything EOP related is now the DAC_V6.lua file, NOT luaPluginScript.lua anymore.
      This was done so it doesn't get overwritten by accident when updating.
- (W) Implemented Faction Specific UI for Bree, Gondor and Mordor (all .bat files and .tga files are stored in lua/Batch_Files)

31st October 2023 

- (L) Updated the traits to account for the new religions, and updated some of the prior ancillary adjustments
- (L) Added Pythax's Mordor UI, UIs for the Gwathuirim temples, and updated the text of those temples slightly to refer to the Gwathuirim religion

30 October 2023

- (W) Added EDU ownership and BMDB textures for Ered Luin Scouts to KD (for Hot7 recruitment)

29th October 2023

- (L) Updated ancillaries to account for the new religions

25th October 2023

- (W) Fixed some typos

21st October 2023

- (Coma)Uploaded new Faolan models with new upgrade models, officers, and bannermen
- (Coma)Uploaded new Khandish General model 

15th October 2023:

- (Lery) Uploaded last new unit for Dale roster completing it with it. Only officer and bannerman is remaining.

12th October 2023:

- (W) In order to address the multiple reports about AI Enedwaith being too strong early game, I nerfed their auto-expansion slightly. They don't get Brêgost anymore and also don't get the two units of Fylani War Wagons. The effects of this need to be tested, of course.

11th October 2023:

- (W) Removed Khamul's Shadow-rangers from the Waystation as they are not AOR restricted.
- (W) Fixed some typos.
- (W) Fixed missing or incorrect greenbook entries for the regions that were added/renamed in v5
- (W) Raised building chain limit from 9 to 40 via EOP (57 is max, if we needed it)
- (W) Set up temple buildings for religions old and new - some descriptions and UI are still missing
- (W) Moved most hinterland_unique buildings into one chain to free up 3 building slots
- (W) Moved all greenbook building chains into 2 chains to free up 6 building slots 

7th October 

- (L) Added Pythax's updated Gondor UI along with an updated cleaner
- (W) fixed the world domination victory message mentioning Caesar, Alexander and Charlemagne

5th October 2023:

- (W) Fixed some typos		

1st October 2023:

- (W) Removed the mention of assassins in the short description for inn buildings.
- (W) Added the information about spies spreading culture in your own settlements to the campaign starting scroll
- (W) Mistven now has Haven Guard, Forthwin has Regent Bowguard, Dinenion has Gondor Infantry. They should now be more useful and survive longer. Also gave Golasgil one more armour upgrade.
- (W) Added the following suggestions by Augimund (tbc):
		- Gave Lurtz lvl 3 armour across all spawns (to match him with Ugluk)
		- Added a shield stat (+1) to Azrazair Warriors and Abrazanim Narduzagar in the EDU to represent the small shield they carry
		- Bree's choice script now starts at turn 41 instead of 66 with the final decision coming at turn 45 instead of 70 (also updated the respective event messages)
		
24th September 2023

- (W) Added the "stat_stl    4" line to the EDU for every unit that is not an elephant, troll, siege or garrison unit. this will kill off units below 4 soldiers after a battle, thus hopefully getting rid of the 3-or-less-soldiers crash.	  
- (W) Removed "stat_stl   4" for all units I previously added it to since it kills custom generals if they end the battle below the threshold. A crying shame indeed.
- (Coma) Updated Dale's non mounted unit cards

23rd September 2023:

- (W) Implemented Defeat Traits. 82 Generals now each give a unique trait when killed/defeated in battle. Works for the AI as well. 
	  (descr_strat, campaign_script, export_descr_character_traits, export_vnvs)
	  
22nd September 2023:

- (W) Changed the roster KD get to train from the Hall of the Seven to avoid overlap with units from their standard roster and to fill a few niches. The new roster contains:
	  Ered Luin Pikemen
	  Ered Luin Scouts
	  Erebor Axethrowers
	  King's Warriors
	  Blacklock Engineers		
	  (export_descr_buildings.txt, export_buildings.txt, campaign_script.txt)	
- (W) added free upkeep for Dwarven Travellers at the Green Dragon in Hobbiton (non-recruitable, though), so Bilbo can become the governor bree players always wanted him to be	

20th September 2023:
- (Lery) Added new visuals to all Gondor Mainline upgrades including the banner. Added a new visual to second upgrade of Lossarnach Axemen. No faction variations for AA and ND yet done

19th September 2023:
- (W) fixed the names of Tusturë, Khargukôr, Darz-Ghûrum and their respective regions in SA, they still had the old region names
- (W) added free upkeep to the Uushixià Stormriders (since War Wagons and Süri'ut Chariots get it, too)

17th September 2023:
- (W) fixed a bug where the Beorning Shieldbearers started with 12 units in their pool upon barracks completion
- (W) fixed a couple typos

16th September 2023: 
- (L) Implemented Louis Lux's Galadriel and Dark Galadriel portraits, CSMs, battle models into the descr_models_strat and BMDB, for future plans involving Galadriel (these are not currently used ingame)
 
10th September 2023: 
- (L) Updated the EBD so that almost all unit entries should now use the correct updated religions (i.e. Harad's units were updated to require Southron instead of Easterling religion). Khand and Dunland's entries will be updated when their scripts are edited. Buildings, uis, scripts, descr_strat, traits, and ancillaries still need to be setup
- (L) Khand now begins as Nomadic from Turn 1; if you side with the Blue Wizards a large percentage of your population converts to Followers of Sauron to represent the backlash. This allows them to have a 100% unique portrait set if one is created for them.
- (L) Dunland will covert to Gwathuirim if you backstab Saruman along with 50% of your population.
- (L) Khand's orthodox EDB unit entries have been thus removed, and Dunland now has entries for both script routes.

4th September 2023: 
- (W) fixed some typos
- (W) fixed Enedwaith's heir having the wrong name in the faction selection screen

3rd September 2023: 
- (L) Overhauled the starting region religions in descr_regions to account for the new religions added in Divide and Conquer 
- (L) Uploaded fixed EOP config files
- (L) Added custom UI pips for the new religions and overhauled some existing ones (and changed their order so similar religions are grouped together in the Enemy Settlement Details screen)
- (L) Updated Bree's custom portrait set to associate it with the Middlemen religion, and Dunland and Enedwaith should now use their pre-v5 mesoamerican portrait sets (since they no longer share a religion with Bree)

27th August 2023: 
- (L) Added initial framework for the religion overhaul (factions now have correct religions assigned to them). Buildings, uis, scripts, recruitment requirements, descr_strat, and portraits still need to be setup
- (L) Updated the string name for Dowinion's cultural building chain to read 'Gardens' (since both men and elves cherish them in Dorwinion)

22 August 2023
- (W) added the string name for Dorwinion's Elven Garden to text/export_buildings.txt
- (W) fixed a couple of typos

15 August 2023: 
- (W) fixed typos in the Rhudaur greenbook
- (L) Updated EOP to 2.2.3

12 August 2023: 
- (L) Dorwinion now has a bespoke religion, Avarin (building art and religion name subject to change)
- EOP LAUNCHER NOW REQUIRED TO LAUNCH DAC 

11th August 2023:
- (Lery) added King and general battle model to the game(Works noice :D). Added a new cavalry unit on Barding tier. Also fixed some stuff that I broke myself :D

10th August 2023:
- (Lery) added Logath units to bmdb and made them work. Changed the type names in EDU and other files for Dale units.

8th August 2023:
- (W) fixed names of Mornedhel and its region in SA, they still had the old ones 										
- (W) fixed all typos up to August 7, 2023 																				
- (W) stored the campaign_script containing the Oin and Ori spawns for the KD Skip in the v5.X Submod Files WIP folder 	
- (L) EOP v2.2.2 has been added to Divide and Conquer (until the DaC_Launcher is updated, M2TWEOP GUI.exe will need to be used to launch DaC for EOP to be enabled)
- (Lery) uploaded most of working models for Dale
