# ENDERAL VR (GOOGLE DRIVE REPACK)

## Table of contents
* [Preamble](#preamble)
* [System Requirements](#system-requirements)
* [Requirements](#requirements)
* [Installation](#installation)
* [MCM Settings](#mcm-settings)
* [Noteworthy mods](#noteworthy-mods)
* [Known issues](#known-issues)
* [Scoped bows](#scoped-bows)
* [Supersampling](#supersampling)
* [Character Customization](#character-customization)
* [Game capture](#game-capture)
* [Language packs](#language-packs)
* [Tools](#tools)
* [Included Mods and Tools (Skyrim VR Installation Folder)](#Included-Mods-and-Tools-Skyrim-VR-Installation-Folder)
* [Included Mods (Mod Organizer 2)](#included-mods-mod-organizer-2)
* [Game Tweaks](#game-tweaks)
* [Changelog](#changelog)

## Preamble
This guide describes how to configure Skyrim VR to play Enderal: Forgotten Stories SE in VR using Mod Organizer 2.  Note that the ONLY version of Skyrim you need is Skyrim VR.  The Steam edition of Enderal SE is based off the Skyrim SE engine which does not support VR.  While it is NOT possible to add VR to Enderal SE, Skyrim VR can be "modded" with Enderal SE's files (available at NexusMods and Steam) which will allow you to play through the entire game in VR!

This guide simplifies the process of configuring all the required Skyrim VR mods and patches necessary to play Enderal SE in VR by using two mod repack files from Google Drive.  The installation process consists of installing Skyrim VR and Mod Organizer 2, followed by extracting two repack files to your Skyrim VR and Mod Organizer 2 folders respectively.  This guide uses a lightweight modlist designed to deliver an optimal VR experience with minimal performance loss.  This modlist was optimized for Virtual Desktop and Air Link and should perform extremely well when playing the game wirelessly.  Special thanks to the Enderal SE modding team and sasa2727 for the VR patch which made this guide possible!

## System Requirements
Minimum:
* CPU: Intel Core i5-6600K or AMD Ryzen 5 1400 or better
* RAM: 8 GB
* OS: Windows 7/8.1/10 (64-bit versions)
* GPU: Nvidia GeForce GTX 970 / AMD RX 480 8GB or better
* STORAGE: 63GB

Recommended:
* CPU: Intel Core i7-4790 or AMD Ryzen 5 1500X or better
* RAM: 8 GB
* OS: Windows 10 (64-bit versions)
* GPU: Nvidia GeForce GTX 1070 8GB or better
* STORAGE: 63GB
* WI-FI: 802.11ac or 802.11ax (for Virtual Desktop or Air Link; optional) 

## Requirements
* [The Elder Scrolls V: Skyrim VR](https://store.steampowered.com/app/611670/The_Elder_Scrolls_V_Skyrim_VR/)
* [Enderal: Forgotten Stories (Special Edition)](https://store.steampowered.com/app/976620/Enderal_Forgotten_Stories_Special_Edition)
* [Mod Organizer 2 v2.4.2rc1.1](https://github.com/ModOrganizer2/modorganizer/releases/download/v2.4.2rc1.1/Mod.Organizer-2.4.2rc1.1.exe)
* [Free NexusMods account](https://www.nexusmods.com/)
* [ModOrganizer_Repack.rar](https://drive.google.com/file/d/17AamKMGMf9Pw0nlUl8MZohHHFYFW5ut6/view?usp=sharing)
* [SkyrimVR_Repack.rar](https://drive.google.com/file/d/17CY_HbxugHL6WRArtworkffGl4bIj-lQ/view?usp=sharing)
	
## Installation
1. Add Enderal SE to your Steam library from [HERE](https://store.steampowered.com/app/976620/Enderal_Forgotten_Stories_Special_Edition/). The game needs to be in your Steam library but does not need to be installed.
2. Install a &#x1F53A; clean copy &#x1F53A; of Skyrim VR from [HERE](https://store.steampowered.com/app/611670/The_Elder_Scrolls_V_Skyrim_VR/).
	 - If you already have a pre-modded Skyrim VR folder and do not wish to uninstall the vanilla game, you can rename your \SkyrimVR\ folder and then redownload a second clean copy of the game from Steam by reverifying the files.  You can then use one copy of the game to continue playing Skyrim VR along with a second copy of the game for playing Enderal VR.
3. Run Skyrim VR one time from Steam and then exit the game.
4. Download Enderal SE from NexusMods OR Steam.
    - a) If using NexusMods files, login to [NexusMods](https://users.nexusmods.com/auth/sign_in) and download Enderal SE from [HERE](https://www.nexusmods.com/enderalspecialedition/mods/1?tab=files)
    - b) If using Steam files, download Enderal SE from [HERE](https://store.steampowered.com/app/976620/Enderal_Forgotten_Stories_Special_Edition/)
5. Download Enderal SE - Update from [HERE](https://www.nexusmods.com/enderalspecialedition/mods/1?tab=files)
6. Download Enderal VR - patch from [HERE](https://www.nexusmods.com/enderalspecialedition/mods/8?tab=files)
7. Extract the contents of SkyrimVR_Repack.rar (This pack contains: SKSE, EngineFixesVR, Binaural 3D Surround Sound, The Sharper Eye, Dragonborn Speaks Naturally) to:  C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR and overwrite files if prompted.
8. Install Mod Organizer 2 from [HERE](https://github.com/ModOrganizer2/modorganizer/releases/download/v2.4.2rc1.1/Mod.Organizer-2.4.2rc1.1.exe)
9. Launch Mod Organizer 2 and select the following options: Next > Create a global instance > Browse > Navigate to "C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR" and click "Select Folder" > Next > Next > Next > Finish
   - After performing these steps, the upper left drop down bar should say "SKSE".  If not... Click the drop down bar > Select Edit > Set "Binary" to "C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR\sksevr_loader.exe" and "Start in" to "C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR" and hit OK. 
10. Navigate to C:\Users\ (Username)\AppData\Local\ModOrganizer\Skyrim VR
11. Delete the \mods\ and \profiles\ folders and replace them with the same folders that are inside ModOrganizer_Repack.rar.  
12. Launch Mod Organizer 2.  
13. Install Enderal SE to Mod Organizer 2
    - If using NexusMods files, drag and drop the "Enderal SE" file from step 4a to the left window pane in MO2.  
    - If using Steam files, open C:\Users\ (Username)\AppData\Local\ModOrganizer\Skyrim VR\mods folder and create an \Enderal SE\ folder.  Copy files from C:\Program Files (x86)\Steam\steamapps\common\Enderal Special Edition\Data\ to \Enderal SE\.  (Skip Skyrim - Animations.* thru Skyrim - Textures.*)
14. Install Enderal SE - Update to Mod Organizer 2 
    - Drag and drop the "Enderal SE - Update" file from step 5 to the left window pane in MO2 and then change the mod name in the Quick Install window to "Enderal SE - Update" when installing.
15. Install Enderal VR - patch to Mod Organizer 2
    - Drag and drop the "Enderal VR - patch" file from step 6 to the left window pane in MO2.
16. Enable "Enderal SE", "Enderal SE - Update", and "Enderal VR - patch" in Mod Organizer 2 by ticking their associated checkbox in the left window pane.
17. Configure Load Order

	* Required Mod Load Order (left side):
		* Enderal SE
		* Enderal SE - Update
		* Enderal SE - Bug Fixes
		* SkyUI
		* JContainers VR
		* moreHUD VR 
		* SkyrimVRTools
		* Enderal VR patch
		* (everything else)

	* Required Plugins Load Order (right side):
		* Enderal Forgotten Stories.esm
		* Enderal SE - Bug Fixes.esp
		* SkyUI_SE.esp
		* AHZmoreHUD.esp
		* EnderalVRpatch.esp
		* (everything else; Enderal SE specific plugins should be placed near the bottom)
		* DynDOLOD.esp (Generated with the DynDOLOD utility and should be placed near the bottom)
		* Synthesis.esp (Generated with the Synthesis utility and should be placed second to last from the bottom) 
		* AllowFastTravel.esp (Must be placed at the very bottom as the above plugins alter world space which will break fast traveling)

17. Configure your mod loadout: 
	* Disable "Dear Diary VR" if you prefer to use the vanilla SkyUI menu.
	* Disable "Smaller HUD for VR" if you prefer a larger font size.  Unfortunately disabling this mod also makes the entire HUD very large and intrusive in VR.
	* Enable "VRIK Rift-Index-WMR Controller Bindings" if using the Valve Index.
	* Enable "High Poly Project" for higher polygon objects.  Improves visuals but may cause minor graphical glitches.   
	* Disable "Caliente's Beautiful Bodies Enhancer -CBBE-" if you prefer vanilla bodies.  Pre-configured as Vanilla NeverNude.
	* Disable "Bijin Skin UNP and CBBE" if you prefer vanilla skin.
	* Enable "Equippable Tattoo Skins UNP + CBBE" if you wish to apply tattoos/bodypaint to your character (female only).
	* Enable "Story Mode" if you wish to enable gameplay tweaks to make the game enjoyable without worrying about micromanaging and difficulty.
	* Enable "Replace spiders with wolfs and bears" if you have arachnophobia!
18. Select Tools > Tool Plugin > INI Editor to tweak your Enderal VR settings via that game's INI files.  (These values are already tweaked for VR.)
19. Make sure "SKSE" is selected in the upper right dropdown bar and click "Run" to launch and play Enderal VR!
	* You can optionally click "Shortcut" underneath "Run" to create a shortcut for launching Enderal VR directly from the Windows desktop!


## MCM Settings
Once you start a new game, you can configure your individual Enderal VR mods through the in-game Mod Configuration Menu (MCM) which is accessible under System > Mod Configuration.  Most MCM settings can be left as default but the following changes are recommended:
* VRIK MCM: 
1. Disable "Adjust Held Weapons Position". (Fixes scoped bow aiming)
2. Select Body Holsters > Scroll down to Left Shoulder Holster > Untick "Visible" (Prevents your bow from clipping into the edge of your FOV when crouching in real life)  
3. Select Controls > Tick "Selfie Mode" if you want to be able to view and take photos of your character in third person.  You can activate and deactivate the third person view by raising your right hand in the air. 

* Spell Wheel VR MCM: 
1. Select Advanced > Set "Slow Time Scale" to 5.  (Enables slow motion when selecting items from the spell wheel)

* R.A.S.S.
1. Select Options > Raining and set this option to "Off" if you dislike waterdroplet effects on the camera when it is raining.
 
# YOU'RE ALL DONE!  ENJOY ENDERAL: FORGOTTEN STORIES IN VR!  ALL STEPS BEYOND THIS POINT ARE OPTIONAL.





## Noteworthy mods
[**Enderal SE**](https://www.nexusmods.com/enderalspecialedition/mods/1?tab=files): Complete Enderal for Skyrim Special Edition.

[**Enderal VR - Patch**](https://www.nexusmods.com/enderalspecialedition/mods/8?tab=files): This mod offers you the opportunity to play Enderal in VR. Supports special gestures when your Skyrim VR window is active in the forefront in Windows.  Raising your right controller above your head will bring up the Hero menu.  Repeating this gesture will close the Hero menu.  Raising your left controller above your head will teleport you to the Akropolis.   

[**Dear Diary VR - Paper SkyUI and Categorized Favorites**](https://www.nexusmods.com/skyrimspecialedition/mods/44874?tab=files): Replacer for Skyrim interface in a paper style.  Disable if you prefer the classic SkyUI interface.

[**VR Menu Mouse Fix**](https://www.nexusmods.com/skyrimspecialedition/mods/33414?tab=files): Enables mouse for SkyUI-VR. You can use your VR controllers to control the menu cursor like a laser pointer.

[**Smaller HUD for VR**](https://www.nexusmods.com/skyrimspecialedition/mods/30726?tab=files): A simple mod that reduces the size of the HUD elements and text by about 50% for added immersion.  Disable if you prefer having a larger font size.  Unfortunately, this is one of the only HUD mods that is compatible with Enderal VR and disabling this mod makes the entire HUD very large and intrusive in VR.  If you find the text too small with this mod enabled, the best workaround is to delete the following file from your MO2 folder: C:\Users\ (Username)\AppData\Local\ModOrganizer\Skyrim VR\mods\Smaller HUD for VR\meshes\skyvr_hmd_info.nif which will increase your text and status bar size while leaving the rest of the HUD at its reduced size.

[**RaceMenu**](https://www.nexusmods.com/skyrimspecialedition/mods/19080?tab=files): A complete overhaul to the character creation menu.  Allows you to customize your avatar and load custom character "presets".  A fun mod if you want to take pictures of your character in VR using the VRIK "Selfie Mode".  The RaceMenu window appears once after the opening mission and can be accessed any time in-game through the console.  Press ~ to access the console.  Enter showracemenu and hit ENTER to bring up the RaceMenu window and then press ~ to exit the console.

[**Flinching for VR Magic can trigger flinching**](https://www.nexusmods.com/skyrimspecialedition/mods/42550?tab=files): A little mod that allows NPCs to flinch when hit by your right fist or melee weapons in either hand.  Flinching animations do not work if you have ranged weapons such as a bow equipped.

[**VRIK**](https://www.nexusmods.com/skyrimspecialedition/mods/23416?tab=posts): VRIK will display the player character's body in SkyrimVR and animate it to match your movements. Weapons can be kept, drawn, and sheathed in up to 14 visible holsters on your body.  Be sure to untick the "Visible" setting for the Left Shoulder Holster in the VRIK MCM.  This prevents your bow from clipping into the edge of your FOV when crouching in real life.

[**VRIK Rift-Index-WMR Controller Bindings**](https://www.nexusmods.com/skyrimspecialedition/mods/23416?tab=files): These control bindings are an optional add-on for VRIK to make it easier to use holsters.  These bindings are disabled by default but MUST be enabled if you are using Index controllers.

[**HIGGS VR**](https://www.nexusmods.com/skyrimspecialedition/mods/43930?tab=files): Hand collision, physics object grabbing, and gravity gloves-style mechanics for Skyrim VR.

[**Spell Wheel VR**](https://www.nexusmods.com/skyrimspecialedition/mods/47630?tab=files): Selection wheel mod for Skyrim VR. It allows you to select spells, weapons, shields, arrows, potions, poisons, food, torch, armors and more without going into a menu very quickly by press of a button or button combinations to spawn the wheel and hold your hand over the item and letting go of the button. It's equipped automatically.  Be sure to set the "Slow Time Scale" to 5 in the Spell Wheel VR MCM if you want a nice slow motion effect when selecting items from the spell wheel.

[**NavigateVR**](https://www.nexusmods.com/skyrimspecialedition/mods/47174?tab=files): This mod brings immersive navigation to VR with a functional compass which is automatically added to your inventory.  While this mod does support equippable in-game maps, there are no available maps for Enderal locations. Replaced default Riften map with a map of Ark from "Maps - SE" to keep the map artwork lore friendly to Enderal.

[**Splashes of Skyrim - VR**](https://www.nexusmods.com/skyrimspecialedition/mods/47710?tab=files): SKSE plugin that adds projectile based water splashes and ripples, and underwater explosions.

[**DragonbornSpeaksNaturally**](https://www.nexusmods.com/skyrimspecialedition/mods/16514?tab=files): Adds speech recognition to Skyrim VR or Skyrim SE so you can recite your dialogue lines to select them.  Requires no speech training!

[**HapticSkyrimVR - Spellcasting and Enhanced Bow and Melee Feedback SKSE Plugin**](https://www.nexusmods.com/skyrimspecialedition/mods/20364?tab=files): SKSEVR plugin to get spell casting and enhanced bow and melee haptic feedback on VR controllers.

[**Simple Realistic Archery VR**](https://www.nexusmods.com/skyrimspecialedition/mods/28524?tab=files): Automatically unequips your arrows after shooting them, then reequips the arrow after pressing the trigger (MCM configurable) over your shoulder. It also has options for binding different arrows to different buttons, for the position and size of the quiver, and options for attribute costs. Up to 25 arrow types can be bound at once.

[**Weapon Throw VR**](https://www.nexusmods.com/skyrimspecialedition/mods/31374?tab=files): Allows you to throw your equipped weapons in VR by holding a button, swinging your hand, and releasing it. All six melee weapon types, shields and torches are supported. Supports vanilla and mod added weapons. Includes Auto-Return and Auto-Aim features. Comes with an MCM to configure every setting.

[**Dual Wield Block VR**](https://www.nexusmods.com/skyrimspecialedition/mods/28456?tab=files): SKSE plugin to let the player block attacks while dual wielding (two weapons or weapon + spell) or unarmed.

[**LocationalDamageSKSE VR**](https://www.nexusmods.com/skyrimspecialedition/mods/26447?tab=files): Locational Damage for SKSE VR! Do extra damage depending on which body part you hit with your arrows or spells.

[**No Stagger Mod**](https://www.nexusmods.com/skyrimspecialedition/mods/16335?tab=files): This mod makes your character unstaggerable.  This prevents you from being stunned in combat and having a bright light flash across your vision.

[**Sprint Jump VR**](https://www.nexusmods.com/skyrimspecialedition/mods/28354?tab=files): An SKSE plugin to allow Sprint Jumping in SkyrimVR. Increase sprint jump height and distance with a multiplier in the config file.

[**Scoped Bows SE**](https://www.nexusmods.com/skyrimspecialedition/mods/912?tab=files): Scoped Bows is a huge weapons mod that adds scoped variants of all bows to the game, designed to be used without crosshair.  You MUST disable "Adjust Held Weapons Position" in the VRIK MCM or aiming through scopes will not work properly.

[**High Poly Project**](https://www.nexusmods.com/skyrimspecialedition/mods/12029?tab=files): This mod greatly improves visuals by switching out many items and objects with more elaborate 3D versions.  Some of the textures/meshes in this mod are not Enderal VR friendly and will cause purple texture glitches.  All known problematic files have been removed but this mod has been disabled by default due to potential bugs.  It contains no plugins, however, and is safe to use and will not break your saved game.  Feel free to experiment with enabling this mod for better visuals and immersion!

[**Caliente's Beautiful Bodies Enhancer - CBBE**](https://www.nexusmods.com/skyrimspecialedition/mods/198?tab=files): Pre-installed using "Vanilla" body shape with "NeverNude" underwear options.  Improves meshes and textures for your body and hands and gives female NPCs a more feminine form while retaining a lore-friendly Enderal aesthetic.  Disable if you prefer vanilla bodies.  Note that while CBBE bodies can be customized for both the player and NPCs using BodySlide, this tool can cause texture and clipping glitches in Enderal.

[**Bijin Skin - CBBE**](https://www.nexusmods.com/skyrimspecialedition/mods/20078?tab=files): Smoother skin for NPCs with less blemishes.  Disable if you prefer vanilla skin.

[**Equippable Tattoo Skins UNP + CBBE**](https://www.nexusmods.com/skyrimspecialedition/mods/39530?tab=files): Disabled by default.  For female players only.  If enabled, this mod allows you to craft up to five unique tattoos at a forge which you can apply to your body from your inventory.  These tattoos are NOT lore friendly but you can overwrite these tattoos in your \mods\Equippable Tattoo Skins UNP + CBBE\textures\actors\character\equipskins\female\ folder with custom bodypaint textures of your choice.  Bodypaint applied to female characters with this mod can be viewed in first person on your VRIK body when playing in VR!

[**Dynamically Disable Eye Adaptation and Bloom**](https://www.nexusmods.com/skyrimspecialedition/mods/2135?tab=files): Disables Bloom to remove the "glow" effect around light sources.  Disable if you prefer having Bloom effects in VR.

[**Storm Lightning for SSE and VR**](https://www.nexusmods.com/skyrimspecialedition/mods/29243?tab=files): A remake of Minty's Lightning mod as an SKSE plugin. The purpose of this mod is stability and scalability. It can summon up to 50 sheet lightnings and 50 fork lightnings per second and up to 31 cells distance. This results in a more natural and enjoyable storm experience.

[**R.A.S.S - Rain Ash And Snow Shader**](https://www.nexusmods.com/skyrimspecialedition/mods/22780?tab=files): "R.A.S.S." adds weather effects to the Player such as water droplet effects in your vision. Disable if you prefer having no weather effects.  You can alternatively disable select weather effects from the R.A.S.S. MCM. 

[**SkyVRaan - Shimmering VR Waters**](https://www.nexusmods.com/skyrimspecialedition/mods/30571?tab=files): Adds a fake reflection effect to Skyrim VR's outdoor water. It breaks up the distant LOD, shows wave movement on the distant water, and gives an illusion of water depth in the distance. Also has improved realism and clarity of near water.

&#x1F53A; **SMALL PERFORMANCE DROP --- For lower end GPUs, you may wish to experiment with disabling "SkyVRaan - Shimmering VR Waters" in Mod Organizer 2.** &#x1F53A;

[**Story Mode**](https://www.nexusmods.com/enderalspecialedition/mods/123?tab=files): Enderal Story Mode includes gameplay tweaks to make the game enjoyable without worrying about micromanaging and difficulty.  Increases health/mana/stamina, movement speed, carry capacity, and mana regeneration.  Decreases cost of leaning books.  Adds health regen, full healing from food, and rebalances damage.

[**Replace spiders with wolfs and bears**](https://www.nexusmods.com/enderalspecialedition/mods/31?tab=files): Replaces spiders with wolves and bears.  Enable if you have arachnophobia! 

[**DynDOLOD**](https://www.nexusmods.com/skyrimspecialedition/mods/32382/?tab=files): Adds distant LOD for objects and trees to Skyrim.  When looking across the horizon in large open areas, this mod allows you to see FAR more detail than what is possible with the vanilla game, even with in-game LOD settings set to max.

&#x1F53A; **SMALL PERFORMANCE DROP --- For lower end GPUs, you may wish to experiment with disabling DynDOLOD by disabling "TexGen_Output" and "DynDOLOD_Output" in Mod Organizer 2.** &#x1F53A;

## Known issues
* Your headset and controllers must be active before launching the game or it will not start.
* The loading screens are broken and no artwork shows up unless TAA is enabled.  TAA should always be disabled, however, as enabling TAA will always cause in-game blur even when tweaked.
* Cutscenes do not work.  Audio always plays against the SteamVR backdrop.  This is a very minor issue as there are only 3 cutscenes in the entire game.  These can be easily viewed on YouTube and two of the videos are introduction videos which play at the beginning of the game.
* You have no avatar during the tutorial.  This is normal as you do not get an avatar until completing the character creation wizard.
* There are some clipping issues with the character creation wizard on the ship.  You may need to step through the wall of the ship or peer above the ship ceiling to view the full menu.
* &#x1F53A; Do not press any triggers during conversations with NPCs.  There is a nasty bug where interrupting dialogue may prevent you from finishing key conversations and will soft lock your game.  The only way to continue is to reload an old save game. &#x1F53A; 
* If you get stuck during quests from animations that do not trigger properly, press "~" with the game in focus on your monitor and type player.tai or enableplayercontrols in the console.
* Loading saved games during the opening tutorial may cause VRIK to glitch out.
* If you need to reset your height in-game, do not run "Floor Fix" through Open VR Advanced Settings as this may causes problems with VRIK where you get stuck in "Sneak" mode.  Recalibrate your height through the VRIK Calibration Power.  You can do this by selecting the VRIK Calibration Power from the magic menu.
* If you are using Virtual Desktop, you may see a subtle "rectangular box" around the edges of the view where the image becomes blurry outside of the rectangle.  This effect is normal and is caused by the foveation used by Virtual Desktop when streaming Enderal VR wirelessly.
* If you are using Virtual Desktop, Mod Organizer 2 may freeze up when starting a new game if SteamVR is already running.  Selecting "Exit SteamVR" from inside of Virtual Desktop before hitting "Run" in Mod Organizer 2 should fix this issue.
* If you have trouble selecting ingredients at alchemy benches, on your left controller be sure to tap the analog stick to the right which should allow you to select ingredients for crafting.
* If you have issues equipping arrows for your bow, you need to reach behind your back in real life to grab an arrow.  This is a feature from the included Simple Realistic Archery mod. 
* If the Hero menu doesn't pop up when raising one controller over your head, make sure the Enderal window is active and in focus on the Windows desktop.
* Crouching in real life will cause a minor "hitch" in your video as you approach the ground.  This is due to the "Automatic Sneaking" feature which is enabled by default.  If you dislike this effect and don't care about physical sneaking, you can turn this feature off from the in-game settings.
* &#x1F53A; If using ENB Particle Patch, Static Mesh Improvement Mod (SMIM), Blended Roads, Water for ENB, Embers XD / Embers HD, or Glorious Doors you must make sure you are NOT using any plugins for these mods.  Only meshes and textures may be used.  Delete ALL .esp files associated with these plugins before launching the game. &#x1F53A; 
* &#x1F53A; Note that with the exception of texture/mesh mods, mods cannot be safely removed mid-savegame. &#x1F53A;

## Scoped bows
* For scoped bow aiming to work, open VRIK MCM and disable "Adjust Held Weapons Position"
* You can add scoped bows to your inventory by pressing "~" with Enderal VR active on your Windows desktop and entering one of the following lines:

    * Player.AddItem 000CC392 1 (Angi's Bow)
    * Player.AddItem 000AB705 1 (Bow of the Hunt)
    * Player.AddItem 0006B9AD 1 (Dravin's Bow)
    * Player.AddItem 00017059 1 (Firiniel's End)
    * Player.AddItem 000C0186 1 (Froki's Bow)
    * Player.AddItem 000F5D22 1 (Gauldur Blackbow)
    * Player.AddItem 000F652C 1 (Nightingale Bow)

## Character Customization
### RaceMenu Presets
You can customize your character's appearance any time in-game by pressing "~" to access the console and entering:  showracemenu.  Note that you should never change your Race or you will lose all your stats.  While your appearance is mostly irrelevant in VR, it can be fun to customize your avatar if you wish to take selfies in VR using the VRIK "Selfie Mode".

If you wish to use a custom RaceMenu Preset, perform the following steps:
1. Download the RaceMenu Preset you want from NexusMods and place any ".jslot" files in C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR\Data\SKSE\Plugins\CharGen\Presets\.  (You will need to create these folders manually.)
2. Install any prerequisite mods for your RaceMenu Preset through Mod Organizer 2.
3. Launch Enderal VR 
4. Once you are in-game, press ~ to access the console.  Enter showracemenu and hit ENTER to bring up the RaceMenu window and then press ~ to exit the console.
5. Click the "Presets" tab in the right panel and then select "Load Preset" on left panel and click the .jslot file for your RaceMenu Preset.   
6. If your RaceMenu Preset uses High Poly Head, select the "Sliders" tab in the right panel > Select "Head" in the top navigation bar in the left panel > Click "Face Part" in the menu below > Tap your analog stick to the right to select the "High Poly Head" version of your RaceMenu Preset.  This will give you a much higher quality face with no jaggies!
7. Select Done > Close > Done
8. To view your avatar, navigate to the in-game menu and select System > Mod Configuration > VRIK > Controls > Tick "Selfie Mode"
9. Return to your game and raise your right hand in the air to enter and exit "Selfie Mode".  You can now see your avatar in third person for taking selfies in VR! 

### Bodypaint
If you like bodypaint, you can actually customize your character with bodypaint and view your bodypaint in VR on your VRIK body.  You cannot apply bodypaint through RaceMenu, however, as RaceMenu treats paint as overlays which won't work properly with VRIK.  To use bodypaint, you need to apply the paint directly to your player's skin texture file using the "Equipable Female Tattoo UNP CBBE" mod.  You can do this through the following steps (female only):
1. Download a CBBE bodypaint mod of interest from NexusMods.
2. Unpack the contents and then extract the contents of the .bsa files with [Bethesda Archive Extractor v0.10](https://www.nexusmods.com/skyrimspecialedition/mods/974?tab=files). 
3. Open the \textures\ folder from the extracted .bsa files and select a .dds file with the bodypaint you wish to use.  Open this file in Adobe Photoshop.  Select Image > Image Size > Set the Width and Height to 2048px and click OK. 
4. Navigate to the \mods\Bijin skin UNP and CBBE\ folder in your Mod Organizer 2 folder.  Search for "femalebody_1.dds" and open this file in Adobe Photoshop. 
5. Select the Photoshop tab with the bodypaint image, then select the entire image with the Rectangular Marquee Tool and then hit Edit > Copy Merged.  
6. Select the Photoshop tab with the Bijin skin image, then hit Edit > Paste.  Save this file in the following location in your Mod Organizer 2 folder: \mods\Equippable Tattoo Skins UNP + CBBE\textures\actors\character\equipskins\female\ and overwrite the existing tattoo1.dds file (Do not overwrite your original file or all NPCs will have warpaint applied to their skin!).  
7. Finally, enable "Equippabe Tattoo Skins UNP + CBBE" in Mod Organizer 2 and launch the game! 
8. Travel to a forge and craft your warpaint as a tattoo.  Bodypaint will be added to your inventory where you can apply it to your body in VR and successfully view it on your VRIK body!

### Custom Armor
You can further customize your character in VR with custom armor mods.  Custom armor mods work fine in Enderal VR with VRIK and HIGGS but most custom armor needs to be spawned into your inventory using the armor item codes via the console.  You can install custom armor and locate their item codes manually by performing the following steps below.
1. Download the custom armor mod of your choice from [NexusMods](https://www.nexusmods.com/skyrimspecialedition/mods/categories/54/).  
2. Install your armor mod and all prerequisite mods through Mod Organizer 2.
3. Install [Bethesda Launcher](https://bethesda.net/en/game/bethesda-launcher).
4. Launch Bethesda Launcher and install Creation Kit: Skyrim.
5. Edit your Windows Registry to allow Creation Kit to work with Skyrim VR.
	* Type "regedit" and hit ENTER in the Windows Search Bar > Navigate to HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Bethesda Softworks 
	* Right click on Bethesda Softworks and create a new Key called "Skyrim Special Edition" if it doesn't already exist.
	* Right click on "Skyrim Special Edition" and create a new String Value called "installed path" with the following value: C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR\
6. Close the Registry Editor.
7. Open C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR\CreationKit.ini and under the [General] section, add the following line: bAllowMultipleMasterLoads=1
8. Extract the contents of your armor mod using WinRAR or 7Zip.
9. Temporarily copy the .esp file from your armor mod to C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR\Data  
10. Launch Bethesda.net Launcher >  Under Games, select Creation Kit: Skyrim and click PLAY.
11. Select File > Data... > Tick the plugin for your armor mod in the resulting window and click OK and YES.  Click "Yes to all" for any Warning messages.
12. Once the plugin is opened, click "Item" > "Armor" under the left hand bar in the Object Window.
13. Enter a snippet of the armor name for your mod in the "Filter" box in the upper left.
14. Under the "Name" field in the Object Window, note the names of EVERY piece of armor from your mod that you wish to use.
15. Close Creation Kit.
16. Delete the .esp file used in Step 9 from your Skyrim VR installation folder.
17. Launch Enderal VR.
18. When in-game, press "~" to open the console.
19. Type: help "ARMOR_NAME_FROM_CREATION_KIT" in quotations i.e. if Creation Kit listed an armor piece that you wanted called Necromancer Purple Boots, you would type: help "Necromancer Purple Boots" and hit ENTER.
20. The console will return the item code for the above item name.
21. Type: player.additem ITEM_CODE 1 i.e. player.additem 45010ADA 1
22. The armor associated with the item code will be added to your inventory.  Press "~" to exit the console.
23. Open your inventory, and you can now successfully equip the armor from your armor mod!  

# Supersampling
* Supersampling can be done via in-game Supersampling and Contrast Adaptive Sharpening (CAS) via The Sharper Eye mod.  For optimal image fidelity and performance, in-game Supersampling should always disabled.  CAS should always be enabled via The Sharper Eye.  This Google Drive repack is pre-configured to supersample the game using The Sharper Eye.
* When using The Sharper Eye for supersampling, pressing the HOME key with Enderal VR active on your Windows desktop will open the built-in Reshade UI. Here you can adjust the parameters for CAS, Contrast, Brightness, and Color Saturation.  Default settings should be optimal for VR.
* In addition to improving visuals with The Sharper Eye, you can continue to supersample Enderal VR through SteamVR, Oculus Tray Tool, or Virtual Desktop.
    * If playing wired with an HTC/Valve/HP headset, increase your SteamVR resolution above 100% to the maximum resolution your GPU can handle.  
    * If playing wired with an Oculus headset, increase your supersampling as high as your GPU can handle via Oculus Tray Tool.  
    * If playing wirelessly with Air Link, increase your supersampling as high as your GPU can handle via Oculus Tray Tool.  For optimal Air Link performance, set your Air Link Bitrate to around 50Mbps.  You can also further optimize Air Link performance by installing [OpenComposite](https://gitlab.com/znixian/OpenOVR/) to your Skyrim VR installation folder. 
    * If playing wirelessly with Virtual Desktop, lock your SteamVR resolution at 100% and set your Virtual Desktop video settings to Low/Medium/High based on your GPU. For optimal Virtual Desktop performance, set your Streaming settings to 60fps @ 80Mbps bitrate with Sliced Encoding enabled.  You can also experiment with toggling Video Buffering ON and OFF.

## Game capture
* If you want to take screenshots or record footage while in VR, use [OBS Studio](https://obsproject.com) with the [OBS OpenVR Input Plugin v1.5](https://github.com/baffler/OBS-OpenVR-Input-Plugin/releases/tag/v1.5).  This will allow you to capture the game in widescreen at a higher resolution than what can be achieved when capturing the game from either the Virtual Desktop or SteamVR mirror window.

## Language packs
Enderal SE supports language packs which allow the game to be played in Chinese, French, German, Italian, Japanese, Korean, Russian, and Spanish.  You can download the packs [HERE](https://www.nexusmods.com/enderalspecialedition/mods/1?tab=files).  Install the language pack via Mod Organizer 2 with a unique name i.e. "Enderal SE - German Language Pack" and place it underneath "Enderal SE" and "Enderal SE - Update" in your mod loadout.  Finally, edit the following line "sLanguage=ENGLISH" with the preferred language in the following three files:
* C:\Users\ (Username)\AppData\Local\ModOrganizer\Skyrim VR\mods\Enderal SE\Enderal - Forgotten Stories.ini
* C:\Users\ (Username)\AppData\Local\ModOrganizer\Skyrim VR\mods\Enderal SE - Update\Enderal - Forgotten Stories.ini
* C:\Users\ (Username)\AppData\Local\ModOrganizer\Skyrim VR\mods\Enderal VR\EnderalVRpatch.ini

## Tools
[**Synthesis v0.18.3**](https://github.com/Mutagen-Modding/Synthesis): A framework and GUI to construct a single Bethesda game patch from many patcher sources. Designed to allow any program to work as a patcher as long as it conforms to the CLI API.

[**Nemesis Unlimited Behavior Engine v0.84-beta**](https://github.com/ShikyoKira/Project-New-Reign---Nemesis-Main/releases): An animation framework that enables behavior mods like CGO, SkySA, Ultimate Combat and most FNIS dependent mods to work together.

[**DynDOLOD Standalone 3.0 Alpha-33**](https://www.nexusmods.com/skyrimspecialedition/mods/32382?tab=files): DynDOLOD is a set of simple tools based on xEdit/xLODGen to automatically create a Skyrim mod based on the load order which adds distant LOD for objects and trees to Skyrim. By combining DynDOLOD with xLODGen users can create drastically enhanced static object LOD + tree LOD and the new, optional dynamic distant object LOD in a few simple steps.

[**xLODGen Beta 81**](https://stepmodifications.org/forum/topic/13451-xlodgen-terrain-lod-beta-80-for-fnv-fo3-fo4-fo4vr-tes5-sse-tes5vr-enderal-enderalse/): Tool for generating terrain LOD.

[**UI Tweaks v1.0**](https://www.nexusmods.com/skyrim/mods/70774/?tab=files): Theme for Mod Organizer, based on the default style with better and cleaner UI elements.

## Included Mods and Tools (Skyrim VR Installation Folder)
[**SKSE VR v2.0.12**](https://skse.silverlock.org): A tool used by many Skyrim mods that expands scripting capabilities and adds additional functionality to the game.

[**EngineFixesVR v1.21**](https://github.com/rollingrock/EngineFixesVR/releases): SKSEVR plugin to fix various issues with the Skyrim Special Edition engine.

[**Binaural 3D Surround Sound for SKYRIM VR v2.3.01**](https://www.nexusmods.com/skyrimspecialedition/mods/26916?tab=files): This mod uses algorithms that can simulate HRTF, allowing for full 3D surround sound with just a normal pair of earphones or headphones. For 1st person use.

[**The Sharper Eye v1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/46999/?tab=files): Get rid of the blur and grey mist in your headset which are clouding your vision. This VR-enabled ReShade build and preset provide the most performance-friendly sharpening filter for Skyrim VR bundled with a subtle touch of contrast, brightness and saturation. All configurable to your liking.

[**xSHADOWMANx's DLL Loader v1.0.0.4**](https://www.nexusmods.com/skyrimspecialedition/mods/3619?tab=files): DLL Loader for Dragonborn Speaks Naturally.

## Included Mods (Mod Organizer 2)
[**Enderal SE v2.0.8**](https://www.nexusmods.com/enderalspecialedition/mods/1?tab=files): Complete Enderal for Skyrim Special Edition.

[**Enderal SE Update v2.0.8.2**](https://www.nexusmods.com/enderalspecialedition/mods/1?tab=files): Update for Complete Enderal for Skyrim Special Edition. 

[**Enderal SE - Bug Fixes v1.26.3**](https://www.nexusmods.com/enderalspecialedition/mods/2?tab=files): This mod fixes several issues with the game and also includes some small gameplay/balance fixes.

[**SkyUI v1.0-beta.4**](https://github.com/Odie/skyui-vr): Elegant, PC-friendly interface mod with many advanced features.

[**JContainers VR v4.1.13**](https://www.nexusmods.com/skyrimspecialedition/mods/16495?tab=files): Extends Skyrim SE Papyrus scripts (or SKSE/C++ plugins) with JSON based serializable data structures like arrays and maps. Embedded Lua interpreter.

[**moreHUD VR v1.0.4**](https://www.nexusmods.com/skyrimspecialedition/mods/33215?tab=files): Adds more information to the HUD about the currently targeted object. Such as ingredients, weapon effects, potions, read books, v/w, enemy level, etc.

[**SkyrimVRTools v2.3-BETA**](https://www.nexusmods.com/skyrimspecialedition/mods/27782?tab=files): Providing OpenVR input information and control as a service to other Skyrim VR mods.

[**Enderal VR - Patch v2.7**](https://www.nexusmods.com/enderalspecialedition/mods/8?tab=files): Mod for playing Enderal in VR (with the SkyrimVR engine).

[**SKSEVR 2.0.12**](https://skse.silverlock.org): A tool used by many Skyrim mods that expands scripting capabilities and adds additional functionality to the game.

[**EngineFixesVR v1.21**](https://github.com/rollingrock/EngineFixesVR/releases): SKSEVR plugin to fix various issues with the Skyrim Special Edition engine.
- Open EngineFixesVR.ini and add the following lines: MemoryManager = false, SelectAllocator = 1.

[**PapyrusUtil VR - Scripting Utility Functions v3.6b**](https://www.nexusmods.com/skyrimspecialedition/mods/13048?tab=files): An SKSE plugin adding several new scripts with native functions that provide various conveniences related to data storage and other misc functions to the scripter/modder.  DynDOLOD requirement.

[**DynDOLOD Resources SE v3.00 Alpha-9**](https://www.nexusmods.com/skyrimspecialedition/mods/32382?tab=files): DynDOLOD is a set of simple tools based on xEdit/xLODGen to automatically create a Skyrim mod based on the load order which adds distant LOD for objects and trees to Skyrim. By combining DynDOLOD with xLODGen users can create drastically enhanced static object LOD + tree LOD and the new, optional dynamic distant object LOD in a few simple steps.

[**Dear Diary VR - Paper SkyUI and Categorized Favorites v1.06**](https://www.nexusmods.com/skyrimspecialedition/mods/44874?tab=files): Replacer for Skyrim interface in a paper style.

[**Dear Diary - Enderal version v2.2.4**](https://www.nexusmods.com/enderal/mods/164?tab=files):  Updates Dear Diary for Enderal compatibility.  Removes "Skills" option from the Tab Menu as this menu is not used by Enderal and will cause the game to crash when accessed if not removed.
- Install Tab Menu ONLY.

[**VR Menu Mouse Fix v1.2**](https://www.nexusmods.com/skyrimspecialedition/mods/33414?tab=files): Enables mouse for SkyUI-VR. You can use your controllers to control the cursor like a smart tv remote.

[**Smaller HUD for VR v1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/30726?tab=files): A simple mod that reduces the size of the HUD elements by about 50%.

[**Dot Crosshair VR v0.8**](https://www.nexusmods.com/skyrimspecialedition/mods/17764?tab=files): Colors the target crosshairs as red and green and converts them to dots since the default grey target crosshairs are often difficult to see and you can not distinguish them in casting double magic.

[**RaceMenu SE v0.4.16**](https://www.nexusmods.com/skyrimspecialedition/mods/19080?tab=files): Complete overhaul to the character creation menu including new customization features such as multiple RGBA warpaints, body paints, hand paint, and foot paints.

[**RaceMenu VR v0.4.14**](https://www.nexusmods.com/skyrimspecialedition/mods/19080?tab=files): VR patch for RaceMenu.

[**Nemesis Unlimited Behavior Engine v0.84-beta**](https://github.com/ShikyoKira/Project-New-Reign---Nemesis-Main/releases): An animation framework that enables behavior mods like CGO, SkySA, Ultimate Combat and most FNIS dependent mods to work together.

[**Spell Perk Item Distributor VR v4.4**](https://www.nexusmods.com/skyrimspecialedition/mods/36869?tab=files): An SKSE plugin that can be used to add spells/leveled spells/perks/items/leveled items/shouts/packages/outfits to every NPC in the game, using config files.

[**Ultimate Combat and Creatures Behaviour compatibility for Nemesis v1.12**](https://www.nexusmods.com/skyrimspecialedition/mods/45966?tab=files): This is just a VERY HACKY compatibility patch thing for creature behaviour edits, Nemesis and Ultimate combat, as more and more mods are coming out effecting creature's behaviours it just makes sense to have something like this instead of it being inside multiple mods.

[**Flinching for VR Magic can trigger flinching v1.361**](https://www.nexusmods.com/skyrimspecialedition/mods/42550?tab=files): A little mod that allows the player and NPCs to flinch when hit.
- Requires patching with Nemesis.

[**VRIK V0.8.1. In-Dev Build 28**](https://www.nexusmods.com/skyrimspecialedition/mods/23416?tab=posts): VRIK will display the player character's body in SkyrimVR and animate it to match your movements. Weapons can be kept, drawn, and sheathed in up to 14 visible holsters on your body. An input gesture system allows users to bind actions to gestures on each hand, reducing the need to open menus. An MCM menu allows full configuration of everything.

[**VRIK Rift-Index-WMR Controller Bindings V2.1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/23416?tab=files): These control bindings are an optional add-on for VRIK to make it easier to use holsters.  The button for shout has been moved to Right A (or the right WMR touchpad), and interact is performed by squeezing the right grip.  Sprinting is now done by squeezing the left grip.  With these "safe" inputs on grips, players do not need to worry about shouting accidentally when grabbing holstered weapons.

[**HIGGS VR v1.1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/43930?tab=files): Hand collision, physics object grabbing, and gravity gloves-style mechanics for Skyrim VR.

[**Spell Wheel VR v1.1.1**](https://www.nexusmods.com/skyrimspecialedition/mods/47630?tab=files): Selection wheel mod for Skyrim VR. It allows you to select spells, weapons, shields, arrows, potions, poisons, food, torch, armors and more without going into a menu very quickly by press of a button or button combinations to spawn the wheel and hold your hand over the item and letting go of the button. It's equipped automatically.

[**NavigateVR v1.4**](https://www.nexusmods.com/skyrimspecialedition/mods/47174?tab=files): This mod brings immersive navigation to VR with a functional compass
- Replace "LHandTamrielSettlements.dds" and "RHandTamrielSettlements.dds" with maps of your choice from the "Maps - SE" mod to make the default Navigate VR map artwork lore friendly to Enderal.

[**Splashes of Skyrim - VR v1.2.1**](https://www.nexusmods.com/skyrimspecialedition/mods/47710?tab=files): SKSE plugin that adds projectile based water splashes and ripples, and underwater explosions.

[**DragonbornSpeaksNaturally - Beta v0.21.0-beta**](https://www.nexusmods.com/skyrimspecialedition/mods/16514?tab=files): Adds speech recognition to Skyrim VR or Skyrim SE so you can recite your dialogue lines to select them.

[**HapticSkyrimVR - Spellcasting and Enhanced Bow and Melee Feedback SKSE Plugin v1.7.2**](https://www.nexusmods.com/skyrimspecialedition/mods/20364?tab=files): SKSEVR plugin to get spell casting and enhanced bow and melee haptic feedback on VR controllers.

[**Simple Realistic Archery VR v1.26**](https://www.nexusmods.com/skyrimspecialedition/mods/28524?tab=files): Automatically unequips your arrows after shooting them, then reequips the arrow after pressing the trigger (MCM configurable) over your shoulder. It also has options for binding different arrows to different buttons, for the position and size of the quiver, and options for attribute costs. Up to 25 arrow types can be bound at once.

[**Weapon Throw VR v1.3.3**](https://www.nexusmods.com/skyrimspecialedition/mods/31374?tab=files): Allows you to throw your equipped weapons in VR by holding a button, swinging your hand, and releasing it. All six melee weapon types, shields and torches are supported. Supports vanilla and mod added weapons. Includes Auto-Return and Auto-Aim features. Comes with an MCM to configure every setting.

[**Dual Wield Block VR v1.5.2**](https://www.nexusmods.com/skyrimspecialedition/mods/28456?tab=files): SKSE plugin to let the player block attacks while dual wielding (two weapons or weapon + spell) or unarmed.

[**LocationalDamageSKSE VR v0.7.1-BETA**](https://www.nexusmods.com/skyrimspecialedition/mods/26447?tab=files): Locational Damage for SKSE VR! Do extra damage depending on which body part you hit with your arrows or spells.

[**No Stagger Mod v1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/16335?tab=files): This mod makes your character unstaggerable. 

[**Sprint Jump VR v1.01**](https://www.nexusmods.com/skyrimspecialedition/mods/28354?tab=files): An SKSE plugin to allow Sprint Jumping in SkyrimVR. Increase sprint jump height and distance with a multiplier in the config file.

[**Enhanced Ragdoll Accuracy Main File v1.02**](https://www.nexusmods.com/skyrimspecialedition/mods/45767?tab=files): Makes in-game humanoid corpses much more believable and immersive through meticulous changes in weight, joints, etc.

[**Scoped Bows SE v1.3.1**](https://www.nexusmods.com/skyrimspecialedition/mods/912?tab=files): Scoped Bows is a huge weapons mod that adds scoped variants of all bows to the game, designed to be used without crosshair.

[**Scoped VR-1-1-1 v1.1.1**](https://www.nexusmods.com/skyrimspecialedition/mods/16666?tab=files): Scoped Bows Remixed meshes designed for VR.

[**Basic Dining Set Replacer 1k v1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/30055?tab=files): A mod that replaces the dining set we often see in farmhouses or taverns in skyrim.

[**Noble Skyrim FULL PACK Performance Edition v5.5.0**](https://www.nexusmods.com/skyrimspecialedition/mods/21423?tab=files): Gives all of Skyrim's architecture a complete new look by changing its textures to custom ones. Beside the architecture, several other things, such as landscape, dungeons (ruins, mines, caves etc.), clutter stuff etc. have been re-textured as well, to match the rest of the mod.
- Recommend placing before other texture packs; Remove "whroughgroundmud.dds".

[**Real Mountains Rebuilt v1.2**](https://www.nexusmods.com/skyrimspecialedition/mods/3704?tab=files): Retexture that enhance the detail of mountains and rocks.

[**Tamrielic Textures SE 1 Landscapes 1K v1.4.0**](https://www.nexusmods.com/skyrimspecialedition/mods/32973?tab=files):  A fresh and complete replacement of all Skyrim landscape textures.

[**CC's HQ Caves - 2K v1.1**](https://www.nexusmods.com/skyrimspecialedition/mods/8448?tab=files): This is a retexture of the Cavewalls and the Cavefloor. All textures handmade using Substance Designer 6.

[**Pine Branches Redone 4K v2.0**](https://www.nexusmods.com/skyrimspecialedition/mods/45294?tab=files): Realistic pine branches replacer. All types covered.  Billboards included.

[**Embers XD v2.2.3**](https://www.nexusmods.com/skyrimspecialedition/mods/37085?tab=files): An overhaul of campfires and other fire sources.
- Delete ESP files.

[**STO - Stars 2K Only small stars v1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/4931?tab=files): Overhauls the stars to 4K from 1K.  Uses small stars only to reduce SDE in nighttime scenes for added immersion.

[**RIS - Real Ice and Snow v2.5.1**](https://www.nexusmods.com/skyrimspecialedition/mods/1484): ONE OF THE BEST SNOW MODS FOR OLDRIM, FINALLY IN SSE WITH UPDATED MESHES AND TEXTURES! Snow that looks like real snow. Icicles that look like real icicles. Icebergs that look like real icebergs. Icefloes that look like real icefloes.

[**Fluffy Snow v1.4**](https://www.nexusmods.com/skyrimspecialedition/mods/8955): Simple texture replacer for snow. The aim is to make the snow a little more fluffy than vanilla.

[**Yee - A new snowflake mod - Cathedral Concept v1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/21559): Made from ~20 micron resolution stereographic photographs produced by the Particle Flux Analytics Multi-Angle Snowflake Camera (MASC).
- Delete ESP files.

[**Remove Blurry Snowflakes v1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/38358): This mod removes the blurry snowflakes by using a transparent texture. The normal snowflakes are still present.

[**Farmhouse Stonewalls 4K 2K by CleverCharff v1.3**](https://www.nexusmods.com/skyrimspecialedition/mods/32582): Replaces ugly farmhouse stonewalls with photorealistic 4K or 2K version. Includes parallax.

[**Glorious Doors of Skyrim v1.03**](https://www.nexusmods.com/skyrimspecialedition/mods/32376): All-In-One pack of all my doors including a handy Fomod installer and a new Dwemer door!
- Delete ESP files.

[**R's Windmill v1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/9884): Adds Renthal311 meshes and textures to Windmills in Skyrim. (Increased Wheels)

[**Rustic Windows - Special Edition v2.0**](https://www.nexusmods.com/skyrimspecialedition/mods/1937): This mod retextures the Skyrim and Dragonborn windows in a lore-friendly way. The window glass has been revised to be thick, textured and insulating. The "opaque" nature of the glass has a purpose. 2K and 1K versions.

[**Vanilla Table Replacers v1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/33041): Replaces some tables of the game specially the main tables for nobles.

[**DUST By Ramccoid v6.0**](https://www.nexusmods.com/skyrimspecialedition/mods/38444?tab=files): This mod retextures the ambient dust particles which float in the air and also the falling dust effect in dungeons and such places.

[**Kanjs - Chaurus eggs and staff v2.1**](https://www.nexusmods.com/skyrimspecialedition/mods/46486?tab=files): A Simple Chaurus Egss Meshes and Textures remade ! With an optional Staff!

[**High Poly Project v4.95**](https://www.nexusmods.com/skyrimspecialedition/mods/12029): An on going process to improve the models of the game with more polygons , UV edits or just replace them all together. SMIM was the inspiration and the lack of similar mods led me to make this.
- Should be installed with a Custom Install.  Skip "Farmhouse Stone Walls" as these are better replaced by seperate mods. Skip "Whiterun Clutter", "Smelter Coal", "Furniture", "Plants", and "Riften 3D Leaves" as these at a minimum are incompatible with Enderal VR and can cause purple texture glitches.

[**Tamrielic Textures Terrain LOD v1.1**](https://www.nexusmods.com/skyrimspecialedition/mods/39563?tab=files): New overhaul for Terrain LOD landscape textures that corresponds with the texture mods you have installed. Generated with xLODGen. Also contains Tree LOD.

[**KS Hairdos SSE v1.7**](https://www.nexusmods.com/skyrimspecialedition/mods/6817?tab=files): KS Hairdos is a hair pack that contains 883 hairstyles. 792 hairstyles are for females, 91 are for males.

[**Caliente's Beautiful Bodies Enhancer - CBBE v1.6.1**](https://www.nexusmods.com/skyrimspecialedition/mods/198?tab=files): A completely customisable female body replacer for TESV: Skyrim.

[**Bijin Skin - CBBE v1.4**](https://www.nexusmods.com/skyrimspecialedition/mods/20078?tab=files): Skin textures for CBBE and UNP made by rxkx22.

[**Equipable Female Tattoo UNP CBBE v1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/39530?tab=files): Mod adds 5 x Equippable Tattoo skins for UUNP or CBBE Options are: Bijin, Leyenda or Fair Skin Complexion.

[**Dynamically Disable Eye Adaptation and Bloom v1.2.0**](https://www.nexusmods.com/skyrimspecialedition/mods/2135?tab=files): Disables the irritating eye adaptation and object blooming through scripting. Compatible with all image space lighting mods!

[**Smoking Torches and Candles SSE v1.76**](https://www.nexusmods.com/skyrimspecialedition/mods/8607): A modification that adds a smoke particle effect to torches used by the player and the NPCs as well as those mounted to the wall. Optional component will add a smoke particle effect to most candles in the game world.
- Added for smoking candles.  Smoking torches appears to not always function.

[**Storm Lightning for SSE and VR v1.4.9**](https://www.nexusmods.com/skyrimspecialedition/mods/29243?tab=files): A remake of Minty's Lightning mod as an SKSE plugin. The purpose of this mod is stability and scalability. It can summon up to 50 sheet lightnings and 50 fork lightnings per second and up to 31 cells distance. This results in a more natural and enjoyable storm experience.

[**Pouring Rain v2.0**](https://www.nexusmods.com/skyrimspecialedition/mods/6077?tab=files): Increases rain particles density during raining weathers.

[**R.A.S.S - Rain Ash And Snow Shaders v3.2.2**](https://www.nexusmods.com/skyrimspecialedition/mods/22780?tab=files): "R.A.S.S." adds visual effects to the Player and NPCs during certain conditions.

[**SkyVRaan - Shimmering VR Waters v1.0.1**](https://www.nexusmods.com/skyrimspecialedition/mods/30571?tab=files): Adds a fake reflection effect to Skyrim VR's outdoor water. It breaks up the distant LOD, shows wave movement on the distant water, and gives an illusion of water depth in the distance. Also has improved realism and clarity of near water.
- Requires patching with Synthesis.

[**Story Mode v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/123?tab=files): Enderal Story Mode includes gameplay tweaks to make the game enjoyable without worrying about micromanaging and difficulty.

[**Myths and Legends VI - The Forgotten One v1.01**](https://www.nexusmods.com/enderalspecialedition/mods/25?tab=files): Adds a new Myths and Legends book, a new dungeon, and a completely new creature with unique mechanics.

[**Playable Half Starling Race v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/100?tab=files): Adds Half Starlings as a playable race.

[**EOP SE - Enderal SE Outposts v1.01**](https://www.nexusmods.com/enderalspecialedition/mods/18?tab=files): Adds order outposts, fortifies some camps with additional protection. 

[**Delectable Docks SE v1.2**](https://www.nexusmods.com/enderalspecialedition/mods/77?tab=files): Adds many details to the docks and harbors of Enderal focused on improving immersion.

[**Riverville Catacombs SE v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/80?tab=files): Forgotten Dungeons implements cut content, originally made by SureAI, with updates and fixes to fit seamlessly into the game.

[**Enderal SE - Undercity Arena Fix v.1.0**](https://www.nexusmods.com/enderalspecialedition/mods/9?tab=files): Reworks the undercity arena to be less cheeseable, bigger and fixes an issue with shadows.

[**Noble Quarter Player Home Redone v1.03**](https://www.nexusmods.com/enderalspecialedition/mods/66?tab=files): Overhauls player home in Nobles Quarter.

[**Patch for Mandragorasprouts' Noble Quarter Player House Redone mod v0.1**](https://www.nexusmods.com/enderalspecialedition/mods/117?tab=files): This mod will fix Display Cases in both Player Homes (Ark Marketplace & Noble Quarter) so they actually work.

[**Forgotten Dungeons - Abandoned Excavation Site v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/110): Forgotten Dungeons implements cut content, originally made by SureAI, with updates and fixes to fit seamlessly into the game.

[**Tamira's Enderal Log Cabin SE - Player Home v1.1**](https://www.nexusmods.com/enderalspecialedition/mods/114?tab=files): A small player home near Riverville.

[**Frostville SE v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/127?tab=files): A small but functional settlement overhaul for the Frostcliff Tavern.

[**Bathhouse Relit v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/90): Makes subtle enhancement to the lighting of the bathhouse.

[**Undercity Relit v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/108?tab=files): Extensive lighting overhaul of the Undercity.

[**EAM SE - Enderal Apothecarii Monastery v1.03**](https://www.nexusmods.com/enderalspecialedition/mods/34?tab=files): Adds the Apothecarii Monastery including: Huge monastery area, over 10 interiors, 2 dungeons and much more.

[**Storeable Phasmalist Talismans v1.01**](https://www.nexusmods.com/enderalspecialedition/mods/68?tab=files): Allows you to store away Phasmalist Talismans.

[**Maps - SE v1.2**](https://www.nexusmods.com/enderal/mods/49?tab=files): You can now buy maps that will show you the landmarks of the region.

[**Unique Armor Sets Replacer Enderal SE v2.3**](https://www.nexusmods.com/enderalspecialedition/mods/27?tab=files): High-quality and lore friendly replacers for many of Enderal's unique armor sets! Converted with SSE nif optimizer.

[**Dawnguard Heavy Armor (Shadowsteel Brigandine) - SE v2.0**](https://www.nexusmods.com/enderalspecialedition/mods/33?tab=files): A port of Dawnguard heavy armor set from Skyrim SE to Enderal SE.

[**Practical Armor Replacers v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/23?tab=files): Armor and weapons more fitting to the setting of Enderal. Converted to SE!

[**Enderal SE - Crossbows v1.07**](https://www.nexusmods.com/enderalspecialedition/mods/4?tab=files): Adds Crossbows to Enderal SE.

[**Unique Enderal Uniques SE v2.0**](https://www.nexusmods.com/enderalspecialedition/mods/38?tab=files): Enderal SE conversion of Unique Enderal Uniques using SSE nif optimizer.

[**Kolapon's Unique Weapons v1.5**](https://www.nexusmods.com/enderalspecialedition/mods/95?tab=files): Gives unique appearance to several of the unique weapons in Enderal and adds a brand new staff to one of the bosses.

[**Static Mushrooms  - High Poly by Malady The Endurant**](https://www.nexusmods.com/enderal/mods/196): Many animated/interactive/static mushrooms across Enderal are high poly now.
- MUST be run through Cathedral Assets Optimizer with the following settings:  SSE Profile, Process Meshes, Full optimization, Always process headparts.
 
[**Craftsman Tools Replacer v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/28?tab=files): Replaces meshes and textures of the crafting tools seen throughout Enderal.

[**Ark Easserspeier - Ark Watersprouts (SE) v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/62?tab=files): Changes the waterspouts in the Foreign Quarter in Ark.

[**Celtic Endralean Penny v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/71?tab=files): A simple mod that replaces the default Enderalean Penny Coin with InsanitySorrow's Celtic coin.

[**Cannons 2K v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/63?tab=files): Replaces the cannons and cannonballs with new 2K textures.

[**Drunken Bee Sign v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/118): Adds a sign to the blank wall on the exterior of the Drunken Bee in Riverville.  

[**Diverse Weather v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/70?tab=files): Diversifies the weather in Enderal and adds a few new ones.

[**Enderal NPC Overhaul - SE version v2.2**](https://www.nexusmods.com/skyrim/mods/85455?tab=files): 75+ important NPCs are given a unique look, 500+ NPCs are given KS Hairdo's Hair. No esp. Can choose only unique, males or females.

[**Kids of Enderal - SE v1.7**](https://www.nexusmods.com/skyrim/mods/93432?tab=files): Remakes kids in Enderal to look like Skyrim's "The Kids are Alright".

[**Stronger Souls v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/113?tab=files): Makes the conjured Souls stronger. 

[**Tharael as Follower and Housemate v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/45?tab=files): Adds an option to make Tharaêl your companion after completing Dark Chambers of Our Mind (providing that you sided with him and offered to help him).

[**Amanda v1.4.2**](https://www.nexusmods.com/enderalspecialedition/mods/15?tab=files): Adds female follower to The Drunken Bee tavern in Riverville.

[**Bears of the North v1.1**](https://www.nexusmods.com/skyrimspecialedition/mods/47541?tab=files): Visual overhaul of the bears of Skyrim. Bigger, badder bears fit for the harsh northern lands they roam.

[**Enderal SE - Bears of the North v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/30?tab=files): Enderal SE compatibility patch for Bears of the North.

[**Creature Replacer Pack v1.1**](https://www.nexusmods.com/enderalspecialedition/mods/74?tab=files): A collection of creature replacers for Enderal converted to SE.

[**Enderal - Arp v2.12**](https://www.nexusmods.com/enderalspecialedition/mods/36?tab=files): Completely redesigned 4K Arps for Enderal SE and VR.

[**Enderal - Vatyr v2.22**](https://www.nexusmods.com/enderalspecialedition/mods/41?tab=files): Completely redesigned Vatyr in 4K for Enderal SE and VR.

[**Enderal - Donkey v2.11**](https://www.nexusmods.com/enderalspecialedition/mods/107?tab=files): Enderal replacer. This changes the textures of donkey.nif & donkey_barrel.nif, every donk.

[**Boneripper Replacer (Clannfear) v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/59?tab=files): Replaces the models Bonerippers with high quality alternatives.

[**Pus Beetle Replacer v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/48?tab=files): Replaces the models Pus Beetles with high quality alternatives.

[**Ancestral Spirit Replacer (Variant 2) v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/60?tab=files): Replaces the models Ancestral Spirits with high quality alternatives.

[**Kolapon's Various Creatures Replacers v1.5v**](https://www.nexusmods.com/enderalspecialedition/mods/64?tab=files): Changes the appearance of some of the creatures so they are unique to Enderal.

[**Kolapon's Undead Creatures Replacer v1.2u**](https://www.nexusmods.com/enderalspecialedition/mods/64?tab=files): Changes the appearance of some of the creatures so they are unique to Enderal.

[**Enderal SE - Predators v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/115?tab=files): Replaces the models of Panthers, Leopards and Shadow/Mountain Deerstalker with alternatives.

[**Dwemer Automatons Glowmapped v2.2**](https://www.nexusmods.com/skyrimspecialedition/mods/48724?tab=files): Adds glow maps to all dwemer automatons.

[**Enderal SE - Dwemer Automatons Glowmapped v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/111?tab=files): Compatibility patch for Dwemer Automatons Glowmapped.

[**Deerstalker (Sabrecat) Replacer v1.01**](https://www.nexusmods.com/enderalspecialedition/mods/122?tab=files): Replaces the Deerstalker (Sabrecat) models with high quality alternatives.

[**Frost Troll Replacer v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/121?tab=files): Replaces the model of Frost Trolls with high-quality alternatives.

[**Dragon Replacer (Variant 3-6) v1.01**](https://www.nexusmods.com/enderalspecialedition/mods/120?tab=files): Replaces the dragon model with high quality alternatives. 

[**Replace spiders with wolfs and bears v1.0.1**](https://www.nexusmods.com/enderalspecialedition/mods/31?tab=files): Replaces spiders with wolves and bears.

[**Nemesis_Output**]: Flinching Animations patch generated with [**Nemesis**](https://github.com/ShikyoKira/Project-New-Reign---Nemesis-Main/releases). 

[**TexGen_Output**]: LOD textures and billboards patch generated with [**DynDOLOD Standalone 3.0 Alpha-33**](https://www.nexusmods.com/skyrimspecialedition/mods/32382?tab=files). 

[**DynDOLOD_Output**]: Object and tree LOD patch generated with [**DynDOLOD Standalone 3.0 Alpha-33**](https://www.nexusmods.com/skyrimspecialedition/mods/32382?tab=files). 

[**xLODGen_Output**]: Terrain LOD patch generated with [**xLODGen Beta 81**](https://stepmodifications.org/forum/topic/13451-xlodgen-terrain-lod-beta-81-for-fnv-fo3-fo4-fo4vr-tes5-sse-tes5vr-enderal-enderalse/).

[**Synthesis_Output**]: SkyVRaan patch generated with [**Synthesis**](https://github.com/Mutagen-Modding/Synthesis/releases).

[**Allow Fast Travel v1.3**](https://www.nexusmods.com/enderalspecialedition/mods/42?tab=files): Allows Fast Travel in Enderal.

## GAME TWEAKS 
Recommended game settings are listed below.  Note that the above Google Drive repack has already been pre-configured with the following tweaks which are merely listed for reference.

### INI Settings
* INI files are found in C:\Users\ (Username)\AppData\Local\ModOrganizer\Skyrim VR\mods\profiles\
* These INI files will override any vanilla INI files which are stored in: C:\Users\ (Username)\Documents\My Games\Skyrim VR\  
* Recommended INI settings: 
1. Open INI files and add this text somewhere under the [Launcher] section: bEnableFileSelection=1 (Enables mods)
2. Open INI files and add this text somewhere under the [Display] section: iTintTextureResolution=2048 (NPC Overhaul tweak)
3. Open INI files and add this text somewhere under the [VR] section: bAllowVRCheating=1 (Disable bumpback when too close to an object)
4. Open INI files and add this text somewhere under the [VR] section: fVrScale=72 (Tweaks world scale for VR; Typical values are between 72-78)
5. Open INI files and add this text somewhere under the [VRUI] section: fHUDCompassScale=0.5000 (Decrease compass size)
6. Open INI files and add this text somewhere under the [VRUI] section: bPlayVRMeleeWorldImpactSounds=0 (Disable impact sounds; Set to "1" if you like the effect.)
7. Open INI files and add this text somewhere under the [VRWand] section: fBowHoldOffsetY=-6.6 (Tweaks bows for VR)
8. Open INI files and add this text somewhere under the [Particles] section: iMaxDesired=1500 (Tweaks Embers XD)
9. Open INI files and add this text somewhere under the [VRUI] section to decrease text size: 

         fActivateRolloverSecondaryScale=10	 
         fActivateRolloverSecondaryZ=0	 
         fActivateRolloverSecondaryY=0	 
         fActivateRolloverPrimaryScale=10	 
         fActivateRolloverPrimaryZ=0	 
         fActivateRolloverPrimaryY=0	 
         fActivateRolloverWandScale=10.0000 	 
         fActivateRolloverSecondaryScale=10.0000	 
         fActivateRolloverPrimaryScale=10.0000
 
### In-Game Settings
1. Set Movement speed to 50%
2. Activate "Physical Sneaking" and "Realistic Bow Aiming"
3. Disable "FOV Filter when Moving"
4. Set Supersampling slider to minimum (all the way left)
5. Disable Dynamic Resolution
6. Disable Temporal AA
7. Disable Foliage Shadows
8. Untick “Disable LOD” options and set the Tree Lod slider to max
9. Enable "Skinned trees"
10. Enable "Animated trees"
11. Distance sliders are set to: Item 20%, Actor 20%, Objects 40%, Grass 100%

### Flinching Configuration 
Flinching adds flinching animations.  NPCs will react with an animation when attacked with the right fist or melee weapons in either hand.  Flinching has been pre-configured with this Google Drive repack but the configuration process has been documented below for reference. 

1. Launch MO2 and select Tools > Executables > Add an executable ("+" icon in upper left) > Add from file > Navigate to C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR\Data\Nemesis_Engine > Select Nemesis Unlimited Behavior Engine.exe > OK
2. Right click on "Overwrite" in the left window pane and select: Clean Overwrite > OK.  (If applicable, this option may not be available if your overwrite folder is already clean)
3. Select Nemesis Unlimited Behavior Engine from upper right drop down and click RUN
4. Click OK for both Warning pop-ups
5. Click "Update Engine"
6. Tick the "Flinching Animations" option and click "Launch Nemesis Behavior Engine"
7. Wait for the process to finish and then close the Nemesis Unlimited Behavior Engine.
8. Right click on "Overwrite" and select "Create Mod".  Enter a custom name i.e. Nemesis output and click OK.
9. Tick "Nemesis output" in the left window pane. 
10. Revert the upper right dropdown bar back to "SKSE".
11. You may need to re-run this process if you change your load order.

### SkyVRaan Configuration 
SkyVRaan adds shimmering water effects to the game.  SkyVRaan has been pre-configured with this Google Drive repack but the configuration process has been documented below for reference.  This process should be run immediately before or after DynDOLOD/xLODGen (if using DynDOLOD/xLODGen).  If you have installed a terrain LOD mod, disable any correpsonding .esm files when patching SkyVRaan as terrain LOD .esm files only need to be active when running DynDOLOD/xLODGen. 

1. If you have updated Synthesis, you MUST remove files from older versions by removing the following folder:  C:\Users\ (My Username)\AppData\Local\Temp\Synthesis
2. Close Mod Organizer 2 if open
3. Create a blank Skyrim.ini file in C:\Users\ (Username)\Documents\My Games\Skyrim VR\
4. Install .NET SDK 5.0 and remove any previously installed .NET runtimes.  You can confirm .NET SDK 5.0 is properly installed by running the following from your command prompt:  dotnet --info
5. Launch MO2 and select Tools > Executables > Add an executable ("+" icon in upper left) > Add from file > Navigate to C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR\Data\Synthesis\ > Select Synthesis.exe > OK
6. Right click on "Overwrite" in the left window pane and select: Clean Overwrite > OK. (If applicable, this option may not be available if your overwrite folder is already clean)
7. Select Synthesis from upper right dropdown and click RUN
8. Select Skyrim VR
9. Select Git Repository (2nd icon in upper left) 
10. Search for SkyVRaan and select the "+" icon next to SkyVRaanAutoPatcher and SkyVRaanWeatherPatcher
11. Click RUN icon
12. Wait for the utility to report "Completed" and close Synthesis.  If Synthesis errors out when patching SkyVRaan, try the following:
	- Select SkyVRaanAutoPatcher and SkyVRaanWeatherPatcher in the left hand bar and set "Mutagen" and "Synthesis" to "Latest".
	- Click "Skyrim VR" in the top bar.  Under Data Folder Location, enter the following path: C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR\Data
13. Right click on "Overwrite" and select "Create Mod".  Enter a custom name i.e. Synthesis output and click OK.
14. Tick "Synthesis output" in the left window pane and make sure "Synthesis.esp" is near the bottom of your Plugin load order and ticked in the right window pane.  
15. Revert the upper right dropdown bar back to "SKSE".
16. You may need to re-run this process if you change your load order.

### DynDOLOD Configuration 
DynDOLOD is a set of simple tools based on xEdit/xLODGen to automatically create a Skyrim mod based on the load order which adds distant LOD for objects and trees to Skyrim.
DynDOLOD has been pre-configured with this Google Drive repack but the configuration process has been documented below for reference.

Note that many DynDOLOD guides on the Web are heavily outdated.  While DynDOLOD is a dynamic patch and thus a bit more complicated to setup versus standard mods, the most recent versions are actually fairly simple to configure.  The following steps outline everything necessary to setup DynDOLOD with Enderal VR.

1. Install [Microsoft Visual C++ Redistributable for Visual Studio 2015, 2017 and 2019](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you don't already have it installed.
2. Extract [SKSE VR](https://skse.silverlock.org/beta/sksevr_2_00_12.7z) to your Skyrim VR installation folder.  If you have already setup Skyrim VR or Enderal VR, this step has most likely already been completed.
3. Install the following prerequisite mods through Mod Organizer 2:
	- [SKSE VR](https://skse.silverlock.org/beta/sksevr_2_00_12.7z) (Scripts folder only)
	- [PapyrusUtil VR - Scripting Utility Functions](https://www.nexusmods.com/skyrimspecialedition/mods/13048?tab=files) (Under "Miscellaneous Files")
	- [DynDOLOD Resources SE 3.00](https://www.nexusmods.com/skyrimspecialedition/mods/32382?tab=files) (Under "Miscellaneous Files")
4. Install a terrain LOD mod through Mod Organizer 2.  If using Tamrielic textures, the [Terrain LOD for Tamrielic Textures](https://www.nexusmods.com/skyrimspecialedition/mods/39563?tab=files) mod is recommended.
	- Place this mod AFTER all other Skyrim SE texture mods in your mod load order in the left window pane.
	- Move the Perfect Terrain LOD.esm plugin underneath Enderal - Forgotten Stories.esm in the right window pane.
5. Download [DynDOLOD 3.00](https://www.nexusmods.com/skyrimspecialedition/mods/32382?tab=files) under "Miscellaneous Files" and extract the contents to a new \DynDOLOD\ directory that is outside of special OS folders like 'Programs Files' or 'Program Files (x86)', Users, Documents, Desktop, Downloads and also not in SteamApps, game or any mod manager folders.
6. Download [xLODGen - Beta 81](https://stepmodifications.org/forum/topic/13451-xlodgen-terrain-lod-beta-81-for-fnv-fo3-fo4-fo4vr-tes5-sse-tes5vr-enderal-enderalse/) and extract the contents to a new \xLODGen\ directory that is outside of special OS folders like 'Programs Files' or 'Program Files (x86)', Users, Documents, Desktop, Downloads and also not in SteamApps, game or any mod manager folders.
7. Launch Mod Organizer 2.
	- Select Tools > Executables  
	- Select Add an executable ("+" icon in upper left) > Add from file > Navigate to "TexGenx64.exe" in the folder created in Step 5 and select "Open" > Type -tes5vr under "Arguments" and click "Apply".  
	- Select Add an executable ("+" icon in upper left) > Add from file > Navigate to "DynDOLODx64.exe" in the folder created in Step 5 and select "Open" > Type -tes5vr under "Arguments" and click "Apply".  
	- Select Add an executable ("+" icon in upper left) > Add from file > Navigate to "xLODGenx64.exe" in the folder created in Step 6 and select "Open" > Type -tes5vr -o:"c:\xLODGen_Output\" under "Arguments" and click "Apply".  
	- Click OK to return to the main Mod Organizer 2 window. 
8.  Select TexGenx64 from the upper right drop down bar and click Run.
	- If you get a "Could not open registry key" error, launch vanilla Skyrim VR one time from Steam.  Then exit Skyrim VR and repeat this step.  (This step can be performed outside of VR.  Simply launching Skyrim VR from your flatscreen and exiting after any Steam VR errors regarding no detected headset is sufficient.)
	- If you get a "Found stitched object LOD textures" error click "Ignore".
	- Click "Start" with default options once the TexGen window appears.
	- Wait for TexGen to finish running, it typically takes several minutes.  When the process completes, click "Exit TexGen".
9.  Close MO2.  Navigate to your \DynDOLOD\ folder from Step 5 and move the \TexGen_Output\ folder to C:\Users\ (Username)\AppData\Local\ModOrganizer\Skyrim VR\mods.  Launch MO2 and enable TexGen_Output in the left window pane.
10.  Select DynDOLODx64 from the upper right drop down bar and click Run.
	- Click "High" once the DynDOLOD window appears.  Wait for DynDOLOD to finish running, it typically takes several minutes.  When the process completes, click "Save & Exit".  
11.  Close MO2.  Navigate to your \DynDOLOD\ folder from Step 5 and move the \DynDOLOD_Output\ folder to C:\Users\ (Username)\AppData\Local\ModOrganizer\Skyrim VR\mods.  Launch MO2 and enable DynDOLOD_Output in the left window pane.
12.  Select xLODGenx64 from the upper right drop down bar and click Run.  
		- Tick all world spaces once the xLODGen window appears.  Tick Terrain LOD.  Leave Objects LOD, Trees LOD, and Occlusion unticked.  Then click Generate.
		- If xLODGen freezes or crashes when running, re-run the process a 2nd time and it should complete successfully.
		- Close the xLODGen window once you see "LOD generation complete".
		
13.  Close MO2.  Navigate to C:\xLODGen_Output\ and move this folder to C:\Users\ (Username)\AppData\Local\ModOrganizer\Skyrim VR\mods.  Launch MO2 and enable xLODGen_Output in the left window pane.
14.  Confirm "TexGen_Output", "DynDOLOD_Output", and "xLODGen_Output" are ticked in the left window pane and ensure DynDOLOD.esp is ticked in the right window pane.
15.  Right click Perfect Terrain LOD.esm in the right window pane and click "Open Origin in Explorer.  You can optionally delete Perfect Terrain LOD.esm as this file is no longer needed once your dynamic patches have all been generated. 
16.  Revert the upper right dropdown bar back to "SKSE".
17.  DynDOLOD is now successfully configured!  You should see FAR more detail in the distance when looking across large open areas of the game!

### Mod Organizer 2 Settings
Required Mod Load Order (left side):
* Enderal SE
* Enderal SE - Update
* Enderal SE - Bug Fixes
* SkyUI
* JContainers VR
* moreHUD VR 
* SkyrimVRTools
* Enderal VR patch
* (everything else)

Required Plugins Load Order (right side):
* Enderal Forgotten Stories.esm
* Enderal SE - Bug Fixes.esp
* SkyUI_SE.esp
* AHZmoreHUD.esp
* EnderalVRpatch.esp
* (everything else; Enderal SE specific plugins should be placed near the bottom)
* DynDOLOD.esp (Generated with the DynDOLOD utility and should be placed near the bottom)
* Synthesis.esp (Generated with the Synthesis utility and should be placed second to last from the bottom) 
* AllowFastTravel.esp (Must be placed at the very bottom as the above plugins alter world space which will break fast traveling) 

When installing mods, if prompted to extract BSA files, select "No".

## Changelog
See [Changelog](https://github.com/Ashok0/EnderalVR/blob/master/CHANGELOG.md)
