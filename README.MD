# RoseGoldAddons
<div align="center">
  <a target="_blank">
    <img alt="version" src="https://img.shields.io/github/v/release/Quantizr/DungeonRoomsMod?color=%239f00ff&style=for-the-badge" />
  </a>
  <a target="_blank">
    <img alt="mcversion" src="https://img.shields.io/badge/MC%20Version-1.8.9-blue?color=%239f00ff&style=for-the-badge" />
  </a>
</div>


# RoseGoldAddons Feature List:
### Keybinds:
All the features below are clickable to open a drop-down with more information inside.
<details><summary>Arrow Align Aura</summary>
	
- Click keybind to instantly solve Floor 7's Phase 3 Arrow Align terminal
- This leaves one item frame unsolved, that has to be solved by hand for the server to properly register
		
</details>
<details><summary>Blood Triggerbot</summary>
	
- Toggle to shoot blood room enemies that are looked at
		
</details>
<details><summary>Brewing Macro</summary>
	
- Toggle to start automatically brewing potions
- Supports Speed and  Weakness potions
- Change modes and other options in the RoseGoldAddons config menu under "Alchemy"
	
</details>
<details><summary>Crop Nuker</summary>
	
- Toggle to start breaking crops in range of the player
- Change configuration in the RoseGoldAddons config menu under "Farming"
	
</details>
<details><summary>Custom Item Macro</summary>
	
- Toggle to start all Custom Item Macros
- See [Explanation of Custom Item Macros](#explanation-of-custom-item-macros)
- Saves between sessions
</details>
<details><summary>Enderman Macro</summary>
	
- Toggle to start Enderman Macro
- Uses Precursor Eye to shoot Endermen around the player
- Change configuration in the RoseGoldAddons config menu under "Macros"
</details>
<details><summary>Foraging Island Macro</summary>
	
- Toggle to start Foraging Island Macro
- Change configuration in the RoseGoldAddons config menu under "Foraging"
- See [Explanation of Foraging Island Macro](#explanation-of-foraging-island-macro)
</details>
<details><summary>Foraging Nuker</summary>
	
- Toggle to start foraging trees in range of the player
</details>
<details><summary>Gemstone Nuker</summary>
	
- Toggle to start mining gemstones in range of the player
- Uses Mining Speed Boost
</details>
<details><summary>Ghost Macro</summary>
	
- Toggle to start looking at closest ghost
- Recommended to use with [other features](#more-info-about-ghost-macro) such as custom item macros
</details>
<details><summary>Hardstone Nuker</summary>
	
- Toggle to start Hardstone Nuker
- Includes powder chest solver
- Change configuration in the RoseGoldAddons config menu under "Mining"
</details>
<details><summary>Mithril Macro</summary>
	
- Toggle to start Mithril Macro
- Automatically mines blocks around the player, using actual head rotations and holding down left click
- Slower than Mithril Nuker but more "Legit"
</details>
<details><summary>Mithril Nuker</summary>
	
- Toggle to start a Mithril Nuker
- Automatically mines mithril around the player
- Change configuration in the RoseGoldAddons config menu under "Mining"
- No failsafes
</details>
<details><summary>Necron Aimbot</summary>
	
- Toggle to lock the player's camera onto Necron's position
- I dont know why this is a feature, blame APhatL
</details>
<details><summary>Powder Chest Macro</summary>
	
- Toggle to automatically solve Crystal Hollows powder chests as they spawn in
- Bundled in with Hardstone Nuker, no need to activate both
</details>

### Config Menu:
- TBA

#### Explanation of Custom Item Macros:
	
Usage: `/usecooldown [milliseconds] [left]`

- Will create a new custom macro for the currently held item

- Use `/usecooldown 7000` to set a custom macro for Wand of Atonement

- Use `/usecooldown 100 left` to set a custom macro for Terminator

#### Explanation of Foraging Island Macro:

 

- Make sure the only 4 dirt blocks in range of the player are the ones to plant the tree on

- Make sure the tree can grow naturally:
	-  There is enough air above the dirt to let the tree grow
	- There are no solid blocks surrounding the tree

- Need to have in hotbar:
	- Treecapitator
	- Jungle / Dark Oak / Spruce Saplings
	- Enchanted Bonemeal
	- Fishing Rod
- Autopet rules: 
	- `When: You throw a fishing hook` -> `Equip Monkey`
	- `When: You gain Foraging XP` -> `Equip Ocelot`

- You can set up a redstone clock hooked up to a dropper system to allow for full automation

#### More info about Ghost Macro:
- A custom macro can be set to automatically use Soul Whip to shoot  at the closest ghost
- A custom macro can be set to automatically use healing items to stay alive


### Installation

Download the newest Release and use it like every other forge mod.

### How to install a forge mod
- [Download the latest forge version](http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.8.9.html "Download Forge")
- Run it to install forge  

- Open minecraft launcher and check if forge's profile is there, if not then you can create it ![image](https://user-images.githubusercontent.com/74936369/111808098-b8d7bf00-88e4-11eb-8a2d-60e93b1406a5.png)
- **Windows**: Press windows+r and type %appdata%/.minecraft/
- **Linux**: .minecraft is located in your home folder. ~/.minecraft
- **Mac**: do ⌘ (Command) + Space type "~/Library/Application Support/minecraft/
- Create a folder called "mods" if it isnt there already. then put the mods you download inside that folder and start minecraft.
                   
### Legal Disclaimer

This was made for educational purposes only, nobody which directly involved in this project is responsible for any damages caused.
**You are responsible for your actions.**
