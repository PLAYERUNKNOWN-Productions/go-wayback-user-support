# Changelog

# Early Access Hotfix #5 - v0.24638
*February 13 2026*

Fixed a bug with the stamina system where after 30 minutes of playtime, players could get into a slowed down state that made running hard/impossible.



# Early Access Hotfix #4 - v0.24486
*February 4 2026*

* Soaked burnable items now don’t cause FPS drops after being placed on heat source and picked up
* Sleep key is updated on the help screen
* Fixed a crash when dying after falling from the Glider
* Items in inventory can now be rotated by the key “R”
* Sliders in the weather section now apply when using the “Apply Mode Settings” button



# Early Access Update - v0.24443
*February 3 2026*

### New Features
* Mud can now freeze and has different states in-between, affecting traversal and movement
* Added first implementation of Sleep system (hold Z key to start sleeping while not at risk of death)
* Clocks can now be found in the world to track time
* Glider added to Free Roam mode
  
### Upgrades & Improvements
* Weather visuals upgraded with improved atmosphere, clouds, fog, and lighting balance
* Improved cabin looting logic, making item placement feel more natural and consistent
* Forest traversal improvements:
  * Smoother stepping over small obstacles
  * Improved mantling and vaulting
* Reduced blocking on rocks, branches, and uneven terrain

### New languages:
* Korean, Russian, and Traditional Chinese

### Fixes & Quality of Life

Traversal & Movement
* Fixed cases where vaulting over logs or obstacles could fail
* Improved mantling animations and camera transitions to reduce snapping
* Added missing height checks for vaulting and ladders
* Removed forced get-up animation after sliding
* Improved dangerous traversal feedback with FOV bloom and vignette effects

Items, Inventory & Interaction
* Fixed items ignoring gravity when dropped (map, clocks, etc.)
* Fixed step counter counting steps while standing still or not registering correctly
* Fixed thermometer and pedometer display issues
* All dropped clothing items are now burnable
* Improved battery usage consistency for flashlights, radio, and cassette player

UI & Menus
* General UI visual pass and alignment fixes
* Fixed stretched images and misaligned text in menus
* Improved sliders for more precise control
* Fixed incorrect or missing key prompts in inventory and help screens
* Added confirmation popups when overwriting save files
* Pause menu navigation and layout improvements
* Added increase / decrease indicators on vitals
* Custom Settings page now merges Custom Settings, Seed and Edit Map
* The Display Prompt UI is now located in Settings

World, Environment & Visuals
* Improved tree, foliage, and rock collisions to prevent snagging or clipping
* Fixed snow, wetness, and overcast lighting inconsistencies
* Improved river depth handling to prevent unintended soaking
* Rocks and buildings now cover the ground from snow and rain building up

Audio
* Fixed crashes and inconsistencies related to audio shutdown
* Resolved issues with custom audio settings reverting on launch
* Fixed a bug where it sometimes sounded like the player was outside when they were inside

Game Logic & Progression
* Fixed achievements unlocking incorrectly or not tracking properly
* Fixed poison, wetness, temperature, stamina, and hunger edge cases
* Fixed scenarios and custom games incorrectly disabling achievements
* Fixed save/load issues affecting shelters, poison state, and player stats

Custom Games & Settings
* Fixed custom maps and seeds not loading correctly
* Added missing custom game settings (day duration, weather change speed)
* Prevented incompatible settings from being selected simultaneously
* Improved custom seed input validation and UI behavior

Stability & Performance
* Fixed multiple crashes related to traversal, audio, UI, and world loading
* Improved memory cleanup and asset handling
* General stability improvements across gameplay and menus

## Currently in Development
* Liquids & Fuel system
* Improved foraging and cooking
* Additional updates to landscape surfaces
* Previously played Seeds history
* Improved sharing options for Custom Settings, Maps, and Game Modes


# Early Access Hotfix #3 - v0.23481
*December 10 2025*

* Fixed an issue where custom audio settings reverted to default on launch until the Settings menu was opened.
* Fixed a bug where custom maps reset to a regular map after loading a saved game.
* Resolved an issue preventing achievements from being unlocked in Objective: Survive and Free Roam modes.
* Improved rolling weather transitions. You can now see weather changes approaching on the horizon over time.


# Early Access Update - v0.23409
*December 9 2025*
 
## New Features
Rolling Weather:
* A new dynamic weather front system adds moving cloud walls and shifting atmospheric effects, letting you see storms coming before they arrive.

New Items: Pedometer & Thermometer
* Track your steps and monitor the external temperature with two new survival tools.

Battery System Expansion
* Flashlights, the radio, and the music player now run on batteries (small/medium/large). Items spawn with swappable batteries by default.

Share Seed / Custom Map Deep Link
* You can now share your world seed and/or custom map directly through DeepLinks.

## Improvements
Forest Traversal Overhaul
* Walking over rocks in spruce and beech forests is now much smoother.
* Reduced cases of getting stuck or snagged on uneven terrain.

Audio & Atmosphere
* River audio now varies depending on river width.
* Improved cloud, light, and atmosphere effects across multiple weather types (Thunderstorm, Overcast, Clear Sky, Wet Haze).

World & Environment
* Updated tree canopies, forest tiles, and ground materials.
* Improved moss, foliage collision, and rock sinking to prevent getting caught on surfaces.
* Weather randomization is now based on seed and similar for all playing that map.

Localization
* Added **Ukrainian, Spanish (Latin American),** and updates to several other languages.
* General localization pass and updated credits.

## Fixes & Quality of Life
* Better feedback when generating custom maps or river schematics.
* Fixed calories, water, and temperature values not saving/loading correctly.
* Fixed cooked food ignoring ingredient calories.
* Fixed several inventory and UI issues. 
* Updated first-person mesh shadows and item handling. 
* Fixed several shelter-related item spawn issues.
* Improved vaulting logic for smoother traversal. 
* Fixed various visual glitches on snow, billboards, doors, shutters, and furniture.
* Added feature to switch to Fahrenheit instead of Celsius for temperature in settings.
* Fixed a bug that caused the character to collide with hanging lights.
* Fixed teddy bear and other items not spawning correctly in starter cabin.
* Fixed a bug where custom settings could be lost when loading the game.
* Added crash location data and stability fixes throughout.
* New audio settings volume sliders for:
  * Environment
  * Character's movement
  * Character's Voice (for misophonia)
  * SFX
  * UI



## Early Access Hotfix #2 - v0.22778
*November 24 2025*

* Fixed saves not working as intended in some Game Modes
* Added more debug information to crashes to help with investigation
* Fixed an issue that caused fuses and other electrical components to stop working after loading
* Fixed an issue with Teddy Bear not spawning as cuddly or visible as intended. Teddy Bear now appears in the starter cabin
* Cabins no longer spawn empty in some instances
* Updated the credits


## Early Access Hotfix #1 - v0.22699
*November 21 2025*

* Fixed common crash after loading a saved game
* Game now saves when using alt-f4 to quit game
* No saving upon death or escape
* Updated game mode selection screen
* Note: we are investigating an issue with saving for the Objective: Survive game mode and hope to have a fix for this soon.


## Early Access Launch Update - v0.22622
*November 20 2025*

### New Features
* Saving – You can now stop and continue your game at any time.
* Achievements – A full achievement set is now available.
* Custom Game Settings – Shape your own survival experience.
* Controller Support – In-game controller support (menus coming later).

### Gameplay & Systems
* Added “New Day” notification in Objective: Survive mode
* Added improved day/night transitions
* Sprint: moved from maintained input to toggle.
* Added Streamer Mode (audio-safe).
* Enabled NVIDIA Reflex and DLSS Frame Generation.
* Added edge-of-world warning text.
* Added graphics Revert Settings auto-restore popup.
* Note: Rangefinders from the Open Beta are undergoing fixes with finding range.

### Fixes & Quality of Life
* Compass blur and map compass bezel issues fixed.
* Added map + player data to death and end screens.
* Fixed items getting wet indoors after loading.
* Corrected key hints for Tab/Inventory.
* Fixed custom weather stopping unexpectedly.
* Fixed small items falling through the floor.

### Map & World
* Improved snow billboard visuals and ground readability.
* Weather distance, fog, and lighting updated for consistency.
* Cardboard boxes in the Weather Tower now provide tinder.

### UI & Visuals
* Updated inventory UI, input prompts, tooltips, and popups.
* Improved vital signs display, and death screen visuals.
* Improved flashlight lighting and fog interaction.

### Items & Interactions
* Improved hotbar visibility and item behavior.
* Correct calorie/water content added to all drinks.
* Fixed cooked food ignoring ingredient calories.


## Open Beta Build Update - v0.21492
*October 28 2025*

### Gameplay & Systems
* New Game Modes menu added with two new Game Modes
* Added **Unstuck button** to the pause menu
* Players’ fingers now appear dirtier to match the environment
* Music player no longer exhibits “haunted” behavior
* Generator updated with new diegetic fuel gauge

### Items & Inventory
* Added new flashlights with different functionalities
* Added a prying tool for destruction

### World & Environment
* New river banks and more river variations added
* Foraging logic updated, mushrooms now spawn more more consistently
* Mud patches are now visible on maps; mud color updated
* Updated areas around cabins with new set dressing
* Fixed floating, misplaced, and clipping objects in several cabins
* Animated roof destruction added

### UI & Other Fixes
* Updated translations
* Adjusted map visuals and behavior; weather tower now displays its area
* Fog reduced under clear and overcast conditions
* Fixed compass disappearing and rotation resetting issues
* Adjusted ladder and shelter collisions to prevent blocking and clipping


## Open Beta Build Update - v.0.20224
*September 23 2025*

### Audio & Atmosphere
- Restored foliage-rustle and rain/hail roof impacts
- Heartbeat now signals dehydration/hunger; intensity scales with risk
- Tinnitus + gradual muffling during critical states

### Visual & UI
- Wet items show blue background in inventory
- Compass shows on map when in any quick-slot
- Skylight intensity now separates day/night; clearer dusk lighting
- Anti-aliasing toggle added to Settings 

### Gameplay & Balance
- Weather Tower is no longer specifically pinpointed on the map. Explore and find a good vantage point to locate it!
- Maps can be more easily found in shelters across the world; each map you find features different nearby locations/information.
- Diesel-generator gas lid no longer stackable under-arm
- Build/destruct range cut to 1.5m (was 3m)
- Door boarding improved: doors are locked when you board a door to a wall with a plank
- Cooking items update calories in real time again
- Medium landing roll slowed 50%; smoother get-up blends

### Items & Inventory
- Bed, oil-lamp, flashlight, walkman, radio collision fixes
- Paper no longer crumples on inspect; lamp glass lights only when on
- Wetness recalculates when moved in hotbar

### Performance & Systems
- Reflections switched to screen-space; minor light tuning
- Fixes for invisible items spawning in shelters

### World & Environment
- LOD fixes on coat-hanger; outhouse-door collision updated
- Removed floating lamp in cabin; added shelf collisions to jetty & shack


## Version: Open Beta Build Hotfix - v.0.19783
*September 4 2025*

- Fixed collision issues on the oil lamp and lighter.
- Resolved flashlight coloring issue.
- Fixed a crash and a softlock.


## Open Beta Build Update - v.0.19627
*September 2 2025*

### Gameplay & Survival
- Hunger and thirst no longer cause instant death
- Poison now has permanent side effects
- Fire effects on the player have been reduced
- Escape screen has a timer

### Items & Inventory
- Added lighter, matchbook, and oil lamps
- Inspecting water containers now shows capacity
- Inventory tooltips are now context-specific (Eat, Drink, Open, etc.)

### World & Environment
- Added audio for rivers
- Fixed rocks so players no longer fall through them
- Fixed hiking stops having higher temperature than the world
- Fixed cabin roofs breaking when first discovered
- More randomness in item spawns, cabin durability, and cabin quality outside exploration zones


## Open Beta Build Update - v.0.19205
*August 18 2025*

### World & Environment
- Improved world generation to reduce players getting stuck in rocks and cliffs

### UI & Visuals
Updated map icons and North indicator
Adjusted temperature display

### Items & Balance
Added a 1L bottle to the starter cabin
Updated balancing for more variety in gameplay


## Open Beta Build - v0.19031
*August 12 2025*

### Interactions & Gameplay
- Drink from rivers without stepping in
- Item detection is more forgiving
- Hold **E** to open backpacks and cooking pots
- Map opens with **M** if quickslotted
- More precise item placement with R
- Destroyed furniture burns longer

### World & Environment
- Storms can now break boarded-up windows
- New interest points near logging cabins
- Pots near starter cabin are now pickupable
- Lowered default indoor temperature
- Added new cliffs

### Items & Inventory
- Spoiled food and torn clothing can appear
- Torn clothing is less effective
- Balanced high-tier clothing spawns
- Reduced burnable items; removed prefab fireplaces
- Milk jugs now make sound when refilled
- Hammer, refillables, and ferro rod show correct crosshair icons

### UI & Visuals
- Poison icon added
- Fingers blacken in harsh conditions
- Boots no longer vanish while crouching
- Fixed inspection bugs and item visuals
- Purple floppy disk correctly labeled
- Fixed player rotation at game start

### Survival
- New **fever system**: extreme temperatures can trigger fever, increasing thirst and temperature sensitivity

### Misc
- Updated translations
- General UI text improvements


## Demo Update 2
*July 21 2025*

### FOV Slider
- A Field-of-View slider has been added to the game settings.

### Interactions 
- Refilling water containers now uses right-click (RMB) instead of E.
- You can now drink from snowy or, if you're brave, muddy ground.
- New input prompts added.
- You can switch on on-screen prompts for item actions.
- The crosshair now animates when you're unable to carry something underarm.
- A circular progress bar appears when holding to interact.
- M opens the map if it is in the hotbar.
- Radio and cassette player volume can be changed in game.

### Mechanics
- Water containers are refillable from snow, but can also store poisonous water.
- Cooking now reduces food size in your inventory — without lowering calories.
- Wild garlic, wild strawberries, and wild carrots now provide better nutrition.

### Inventory 
- Tin cans are now treated separately by type — they no longer stack into the same hand.
- The flashlight correctly shows whether it's on or off inside shelters.
- Waterproof backpacks now protect stored items from rain and help them dry.
- Backpack sizes are now displayed accurately when inspecting them.
- Clothing insulation has a greater effect on your body temperature.
- More clothes can get damaged.

### Environment 
- Added a miniature landscape diorama inside the Weather Tower showing your journey.
- Improved liquid rendering when holding containers.
- Breakable furniture added — cabin tables and chairs can now be destroyed. 
- Map start location and Weather Tower location are now accurately marked.
- Improved rock formations in European Beech areas.

### Balancing updates
- Balanced items and consumables available from the starting cabin.
- Balanced wetness from swimming, its more dangerous now.
- Rare waterproof and insulated clothing is even rarer now. 
- Balanced getting dry to make it harder. It won't happen until certain conditions are met, e.g. the world temperature is above 2C.
- All shelters now start at the world temperature, its easier to die at the start.
- Fires are harder to maintain in storms, look for rocky outcrops if you are outside.

### Audio
- New audio mix.

### Other Bug fixes
- Various minor other bug fixes


*June 30th 2025*

## Version: Demo Update 1

### Updates:
- 10 new map seeds replacing the previous 4
- Additional help screen added upon start-up. Press H in-game to display the help screen in-game.
- Other small bug fixes.


*June 25th 2025*

## Version: Jun 25 Playtest Demo Build

### World & Environment
- Updated map visuals, riverbed, and background landscape heightmap.
- Improved terrain blending and snow level calculation.
- Reworked cabin/shelter spawning logic (improved terrain adherence, avoided overlap with starter cabin).
- Distance roof meshes swap dynamically within 50m.
- Enhanced environmental realism: snow cover, fog, "wet haze", and overcast effects.

### Gameplay & Mechanics
- Food becomes a "meal" upon entering pot.
- Cooked food size scales with ingredients.
- Cooking duration depends on ingredient size/count.
- Poisonous food system introduced.
- Wetness affects body temp without clothing. 
- Food containers restricted to food items only.
- Lucy can now drink directly from rivers.
- Added getup animation after sliding, vaulting tweaks, better sprint posture.
- Items now show family tags and proper quickslot counts.
- Inventory hotkey changes and tooltip improvements.
- Inspect item toggle added (Q).

### Fixes & Improvements
- Fixed item pickup, placement material, cooking visuals, and interaction issues.
- Resolved item physics bugs, tooltip spam, and spawn misalignments.
- Addressed flare bugs, map scale readability, walkman animations.
- Fixed heat interaction with objects (stove plates).
- Improved placement & interaction with map, rivers, shelters, and furniture.
- Improved teleportation, falling item logic, and collision settings.

### Assets & Visuals
- Replaced decals with static meshes for maps.
- Added reflection captures, updated shadows and light logic.
- Improved icons (clothing, food, mushrooms, UI polish).
- Visuals for cooked food now persistent and serialized.

### Audio & VFX
- Fixed audio not resuming after game restart.
- Adjusted flashlight SFX, footstep audio integration, fridge proximity logic.
- Added destruction sounds for shelters, map folding sound, and sliding anim feedback.
- Updated fire particle systems and stove heat behavior.

## Changelist 0.15504

## Gameplay Changes
- Terrain generation is now multi-threaded for faster loading.
- Forest items now pull toward the player when picked up.
- Paper can now burn when dropped on a hot stove.
- World items can be consumed directly by holding E.
- Logs are burnable again, with adjusted size and burn duration.
- Upper clothing now affects how wetness transfers between layers.
- Hunger and thirst bars now preview consumed calories.
## Bug Fixes
- Fixed multiple crashes related to eating or equipping items.
- Fixed a bug where equipped items would drop instead of being thrown.
- Fixed a bug where water bottles could be used infinitely.
- Fixed an issue where forageables would vanish if inventory was full.
- Fixed issues with wearable items from the hotbar.
- Logs now correctly rotate and render in first person.
- Placing items now respects the proper delay and position.
- Fixed backpacks showing at feet or becoming unselectable.
- Compass now unzooms correctly when unequipped.
- Lightbulb animations now sync with player movement.
- Fixed inventory and hotbar issues after loading a save.
## Visual & UI Updates
- Map icons and question marks cleaned up for clarity.
- Map now has a scale and updated icon visuals.
- Vitals bar visuals updated; now shows environmental temperature.
- Improved lighting in indoor and overcast conditions.
- Added river crossing visualization and foam effects.
## Audio Improvements
- Restored sliding sounds and added manual slide controls.
- Improved radio behavior when stored or game paused.
- Added contextual hammer sounds and updated footstep audio.
## Performance & Technical
- Terrain generation optimized with multi-threading.
- Reduced physics bugs when interacting quickly with items.
- Fixed memory crashes and data corruption related to item stacking and use.
- Fixed sync and animation issues when interacting with objects.
- Improved handling of localized fonts and translations (JP/CH).
## Various Content Additions

## Version: Feb 25 Playtest Build

As public playtests are ongoing, we will start sharing our changelog with community. **But, because we are not released we don't want to spoil the game.** We will therefore not include notes on new items, mechanics, or systems that we haven't talked about or players have not yet seen. This time the focus is on updates and changes to features since the last playtest in December.

While the following text has some spoilers removed, for purists all updates on this channel will carry a spoilers flag until launch.

## World & Environment Adjustments  
- Update to Rivers. These now have more variation and present a more interesting challenge. 
- Mud is stickier and easier to spot. 
- Improved rules for cabin and shelter spawning. 
## Visual & UI Improvements  
- New UI design for the inventory (visual upgrade) 
- New death screen with stats/info. 
- Updated UI icons 
- New visuals for handheld map item, including key locations. 
- Updates for player character, including textures and mesh. 
- New information flair text for clothing and tools. 
- Improved (and generally made more impressive) fire and combustion visuals. 
## Inventory & Item Handling  
- Fixes and updates to drag-to-drop inventory and hotbar. 
- Items and the player now become wet. 
- Updates to cooking system. 
- Updates to backpack animations and behaviours. 
## Physics & Collision Fixes  
- Fix fall damage triggering temperature highlight on the death screen  
## Rendering & Shader Updates  
- Fog, Atmosphere, Light, Exposure, Cloud Height and Size edits to prevent the milky look from appearing.
## Audio & Sound Effects  
- Improved collision sounds which were sometimes absent or too frequent. 
- New cooking sounds. 
- New fire and combustion audio. 
- New map audio - picking it up, raising it, lowering it. 
## AI & Gameplay Fixes  
- Prevent using a tool while an animation is playing (fixes ferro-rod spam). 
- Fix a bug where foraged items were not pulled towards the player and acted weirdly. 
- Items (including foraged items) can now be stacked under the arm. 
- Camera no longer shows a gross neck hole when looking down. 
## Miscellaneous Fixes & Changes  
- Various Bug fixes, most importantly player won't be spawning in or on the cabin roof anymore!  
## Code & Backend Improvements  
- Added support for container inventories (a crate, box, etc.) - but we don’t have that many in the build yet.  
- Updated starter cabin with paintings. 
- New boot flow, with faster start up.
