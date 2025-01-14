﻿The Extended Player Inventory feature from OdinQOL, pulled out for your modular pleasure. Make your inventory larger, have quickslots, etc.


`This mod uses ServerSync internally. Settings can change live through the BepInEx Configuration manager or by directly changing the file on the server. Can be installed on both the client and the server to enforce configuration.`


### Request of the community to make it modular, resulted in separation of features.


> ## Configuration Options
`[General]`

* Force Server Config [Synced with Server]
    * Force Server Config
        * Default value: true
* Enabled  [Synced with Server]
    * Enable the entire mod
        * Default value: true

 `[Extended Inventory]`
* ExtraRows [Synced with Server]
    * Number of extra ordinary rows. (This can cause overlap with chest GUI, make sure you hold CTRL (the default key) and drag to desired position).
        * Default value: 0
* AddEquipmentRow [Synced with Server]
    * Add special row for equipped items and quick slots. (IF YOU ARE USING RANDY KNAPPS EAQs KEEP THIS VALUE OFF).
        * Default value: false
* DisplayEquipmentRowSeparate [Synced with Server]
    * Display equipment and quickslots in their own area. (IF YOU ARE USING RANDY KNAPPS EAQs KEEP THIS VALUE OFF).
        * Default value: false
* HelmetText [Not Synced with Server]
    * Text to show for helmet slot.
        * Default value: Head
* ChestText [Not Synced with Server]
    * Text to show for chest slot.
        * Default value: Chest
* LegsText [Not Synced with Server]
    * Text to show for legs slot.
        * Default value: Legs
* BackText [Not Synced with Server]
    * Text to show for back slot.
        * Default value: Back
* UtilityText [Not Synced with Server]
    * Text to show for utility slot.
        * Default value: Utility
* QuickAccessScale [Not Synced with Server]
    * Scale of quick access bar.
        * Default value: 1
* Hotkey1 [Not Synced with Server]
    * Hotkey 1 - Use https://docs.unity3d.com/Manual/ConventionalGameInput.html
        * Default value: Z
* Hotkey2 [Not Synced with Server]
    * Hotkey 2 - Use https://docs.unity3d.com/Manual/ConventionalGameInput.html
        * Default value: X
* Hotkey3 [Not Synced with Server]
    * Hotkey 3 - Use https://docs.unity3d.com/Manual/ConventionalGameInput.html
        * Default value: C
* ModKey1 [Not Synced with Server]
    * First modifier key to move quick slots. Use https://docs.unity3d.com/Manual/ConventionalGameInput.html format.
        * Default value: Mouse0
* ModKey2 [Not Synced with Server]
    * Second modifier key to move quick slots. Use https://docs.unity3d.com/Manual/ConventionalGameInput.html format.
        * Default value: LeftControl
* quickAccessX [Not Synced with Server]
    * Current X of Quick Slots (Not Synced with server)
        * Default value: 9999
* quickAccessY [Not Synced with Server]
    * Current Y of Quick Slots (Not Synced with server)
        * Default value: 9999


> ## Installation Instructions
***You must have BepInEx installed correctly! I can not stress this enough.***

#### Windows (Steam)
1. Locate your game folder manually or start Steam client and :
    * Right click the Valheim game in your steam library
    * "Go to Manage" -> "Browse local files"
    * Steam should open your game folder
2. Extract the contents of the archive into the BepInEx\plugins folder.
3. Locate odinplus.qol.OdinsExtendedInventory.cfg under BepInEx\config and configure the mod to your needs

#### Server

`If installed on both the client and the server syncing to clients should work properly.`
1. Locate your main folder manually and :
   a. Extract the contents of the archive into the BepInEx\plugins folder.
   b. Launch your game at least once to generate the config file needed if you haven't already done so.
   c. Locate odinplus.qol.OdinsExtendedInventory.cfg under BepInEx\config on your machine and configure the mod to your needs
2. Reboot your server. All clients will now sync to the server's config file even if theirs differs. Config Manager mod changes will only change the client config, not what the server is enforcing.


`Feel free to reach out to me on discord if you need manual download assistance.`


# Author Information

### Azumatt

`DISCORD:` Azumatt#2625

`STEAM:` https://steamcommunity.com/id/azumatt/


For Questions or Comments, find me in the Odin Plus Team Discord:
[![https://i.imgur.com/XXP6HCU.png](https://i.imgur.com/XXP6HCU.png)](https://discord.gg/Pb6bVMnFb2)

***
> # Update Information (Latest listed first)
> ### v1.0.0
> - Initial Release