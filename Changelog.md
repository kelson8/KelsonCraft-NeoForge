# Changelog for KelsonCraft Pack

## 0.2.0

**Mods added:**

 * [Gravestone Mod](https://modrinth.com/mod/RYtXKJPr) - Graves on death
 * [RSInfinityBooster]() - Refined Storage infinite range
 * [Create Railways Navigator](https://modrinth.com/mod/Dq3STxps) - For Create trains
 * [Saturn](https://modrinth.com/mod/2eT495vq) - Performance improvements
 * [Create Track Map](https://modrinth.com/mod/NHRXB9Bi) - Create track map for local browser viewing.
 * [Load My F\*\*\*ing Tags](https://modrinth.com/mod/67kVxsaO) - Load the pickaxe mineable tags and others, this should solve conflicts.
 * [Productive Bees](https://modrinth.com/mod/jH6iiqkd) - Adds more bee variants for farming them.
 * [ProbeJS](https://www.curseforge.com/projects/585406) - This is just for scripting, I may disable this in the pack later.
 * [KubeJS Offline \(NeoForge\)](https://modrinth.com/mod/7I1fu1km) - This is for keeping an offline documentation of KubeJS for scripting, this can be disabled.
 
 
**Mods removed:**
 * Ballistix
 * Blast Craft
 * CCBX
 * Chemical Science
 * Dynamic Electricity
 * Electro Dynamics
 * Extended Tools
 * Modular Force Fields
 * Nuclear Science 
 * Ultimate Pickaxes
 * Volatic 

## 0.2.1
  I updated Create Enchantment Industry from 2.3.0 to 2.3.1.
  Also, I updated Sable from 1.1.3 to 1.2.2, to hopefully fix the mechanical grindstone
   for Create Enchantment Industry.
   
**Mods updated**
  * Create Aeronautics - Updated from 1.1.3 to 1.2.1.
  * Create Enchantment Industry - Updated from 2.3.0 to 2.3.1.
  * Create Deco - Updated from 2.1.2 to 2.1.3
  * Create Railways Navigator - Updated from 1.21.1-alpha-0.9.0-C6+2 to 1.21.1-beta-0.9.0-C6
  * Create: Dragons Plus - Updated from 1.8.7 to 1.10.0b
  * Create: Numismatics - Updated from 1.0.19 to 1.0.20
  * Create: Power Grid - Updated from 0.5.4 to 0.5.5.1
  * Create: Solar Powered - Updated from 1.2.5 to 1.2.7
  * Sable - Updated from 1.1.3 to 1.2.2

----  

**Misc changes**
    
  * Added the Crafting Recipe Exporter mod to the pack for development, it should allow me to export custom recipes with a GUI for KubeJS.
  
  * Added the `tools.js` script into kubejs/server_scripts/Tweaks, this will allow me to disable a lot of the extra tools that some of my mods add in. 
  
  * Added some basic quests with FTB Quests, these are very incomplete and a work in progress, There is still some work that needs to be done before I have all the quests setup in this mod pack.
  * Changed the `bcc-common.toml` config file to name the pack `KelsonCraft Pack` and set the version.

  * Saved my mod pack options and keybinds with `/defaultoptions saveAll`, So now, anyone using the pack should have a default set of keybinds
  
**Keybind list (These can be changed to your liking)**
  
   * R - Sprint
   * G - Open Backpack
   * M - Open minimap
   * Z - Work in progress, enlarges minimap and toggles Quark inventory switcher.
   * Left Control - Zoom
   * H - Create new waypoint on minimap
   * U - View list of waypoints on minimap
   
   There may be more keybinds that I have changed for this.

----

  I enabled the whitelist by default for the e4mc config, which makes LAN connections private by default,
   so I figured it would be a good idea to enable that.
  You can whitelist someone to join your LAN world with the `/whitelist` command.
  
  Mods removed:
   * Craftable name tags - I have this in my KubeJS scripts.
   * KubeJS Offline - For scripting development
   * Mekanism Tools
   * ProbeJS - This is just for scripting development.
   * Yet Another World Protector - This is mostly a server side claim protection mod.
   
  **Config changes**
   
   * Disabled vertical trees for the Panda's Falling Trees mod, and also disabled it on cactus and bamboo.

# 0.2.2
  * Disabled the snow fall in winter time with the seasons mod, so snow isn't always in the normal biomes.
	
  * Removed the Inventory Profiles Next config folder since it contains user specific world stuff.
   
   Modified some configs in Advanced Peripherals
   * Disable player detector for spectator players.
   * Make chat box not able to execute commands.
	
   * Added the Create Power loader mod for using Create chunk loaders.
	
   * Changed the Window Title with the KubeJS client.json config to `KelsonCraft Pack`.
   
 
   * Added the powah.js script to `kubejs/server_scripts/Tweaks`, It allows me to use the blasting recipes and have the Create attribute filter work for stuff like Uraninite, I may rename this file later.
 
 
---

Updated with changes from 5-7-2026 at 12:05PM to 5-11-2026 at 1:06PM in local Changelog.txt

# 0.3.0  
  Mod Changes:
   * Removed the True Darkness mod since I'm not really using it.
   * Added enderio script for Kubejs to make the dark steel work for steel ingots.
   * Added the logs-to-chest.js Kubejs script into server scripts, it allows me to convert 8 logs of any type into chests.
   
  Added the gamemode-commands.js Kubejs script into server scripts, it adds these command aliases for gamemodes:
  * /gmc /gm1 - Go into creative
  * /gm0 /gms - Go into survival
  * /gma - Go into adventure
  * /gmsp - Go into spectator
  
  * Changed the Refined Storage controller energy capacity from 1000 to 50000, it didn't have enough power for the infinity booster card.
   
  * Fixed some KubeJS errors.
  * Changed Advanced Backups max backup size from 50GB to 10GB to save on space, this can be configured to your needs.
   
   Mods added:
   * AE2 JEI Integration - This is for JEI to display AE2 recipes.
   * Apothic Spawners - This can be used to add different traits to mob spawners and modify them.
   * Create Slice and Dice - For automating Farmer's delight recipes with Create.
   * Creeper Overhaul - Adds more creepers.
   * Cucumber library
   * Ender Storage - Like ender chests but can have channels
   * Ender Tanks - This is for transporting lava from the nether easily and other fluids if needed.
   * Extra Storage - This is for Refined Storage.
   * Flux Networks - Allows for wireless power transfer for Forge Energy and other methods of power.
   * Hostile Neural Networks - For making mob farms
   * Just Enough Resources - This is for JEI to display the chances of mob drops and other items.
   * Modular Routers - Mostly for mob farms
   * Mystical Agriculture
   * Mystical Agradditions
   * Mystical Customization
   * Not Enough Wands - Makes building and somethings easier with wands.
   * Pylons - This is mostly for auto harvesting crops with Mystical Agriculture.
   * Reliquary Reincarnations - This is for automating Inferium growing from Mystical Agriculture.
   * RFTools Base - Base for all RFTools
   * RFTools Dimensions - Multiple dimensions by being powered
   * RFTools Utility - Utility functions for RF Tools

   Mods removed:
   * Iron Ladders - I have the faster ladder climbing mod so these might be a bit too overpowered.
   * Metal Barrels - I mostly just use Sophisticated Storage or Functional Storage instead of these.
   * Simple Belts - This is already done with Create.
   * True Darkness - I was never using this in the mod pack.

# 0.3.1

   Mod Changes:
   * Raised wireless grid, portable grid, and wireless autocrafting monitor from 1000 energy stored to 50,000 energy stored.
   * Disable energy usage for opening the portable grid and wireless autocrafting monitor.
   * Updated Sophisticated Core, Sophisticated Storage and Sophisticated Backpacks to latest version.
   * Changed rs infinity booster cards, set infinity card to need 300 energy, and dimension card to need 500 energy.
   * Disable phantoms spawning with the Bad Mobs config.
   * Updated Xaero's Minimap and Xaero's World Map to the latest version.
 
   Mods Added:
* AdvancedAE
* AE2 Import Export Card
* AE2 Network Analyser
* AE2 Crafting Tree
* AE Infinity Booster - Add infinity boost range for AE2.
* Applied Mekanistics - Adds support for Mekanism to AE2
* Applied Flux - This allows me to store energy generated from my power systems into an AE2 system.
* Bad Mobs - This allows me to disable spawning of certain mobs, for now I'll disable the phantoms.
* Bad Wither No Cookie Reloaded - Make wither spawn, dragon spawn, and thunder sounds local to the player, so only one person will hear those. 
* Better P2P - P2P management tool for AE2.
* Cable Facades - Add cable facades for hiding items and making builds look nicer.
* Chisel - I thought this mod was already on here, for more chisel items.
* Colorful hearts - Makes more then 10 hearts change colors instead of stacking up on the screen.
* Expanded AE
* ExtendedAE - For easier AE2 automation.
* Factory Blocks - Adds new blocks for factories.
* Fast Suite - Performance improvements for the JSON recipe system.
* FTB JEI Extras
* Glodium - Library required for Applied Flux.
* Iron Jetpacks - Re-enabled this mod to use in the mod pack for jetpacks.
* Rechiseled Chipped
* Rechiseled Create
* Sophisticated Storage Create integration
* Wither Skeleton Tweaks - Make all skeletons in the nether wither skeletons.   

-------