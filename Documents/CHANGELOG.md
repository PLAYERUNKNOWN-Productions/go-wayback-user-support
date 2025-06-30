# Changelog

*June 30th 2025*

## Version: Demo Update 1

### Updates:
- 10 new map seeds replacing the previous 4
- Additional help screen added upon start-up. Press H in-game to display the help screen in-game.
- Other small bug fixes.

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
