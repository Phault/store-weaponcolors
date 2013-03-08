store-weaponcolors
============

### Description
Store module that allows players to buy custom weapon colors for their weapons in the store.

### Requirements

* [Store](https://forums.alliedmods.net/showthread.php?t=207157)
* [SDKHooks](http://forums.alliedmods.net/showthread.php?t=106748) 
* [SMJansson](https://forums.alliedmods.net/showthread.php?t=184604)

### Features

* **Customizable** - You can have any amount of weapon colors you want.

### Installation

Download the `store-weaponcolors.zip` archive from the plugin thread and extract to your `sourcemod` folder intact. Then open your store web panel, navigate to Import/Export System under the Tools menu, and import configs/store/json-import/weaponcolors.json.

### Adding More Colors

You can use the web panel to add weapon colors. Open the web panel, navigate to Add New Item under the Items menu. In type and loadout_slot, type weaponcolors. Change name, display_name, description and attrs to customize the new color. 

The attrs field should look like:

    {
        "color": [255, 0, 0, 255]
    }

