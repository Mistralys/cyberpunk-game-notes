# Cyberpunk Game Notes

Modding notes for Cyberpunk 2077

## Mod list

### Legend of requirements

Throughout this document, any dependencies to other mods are added 
between parentheses. The following markers are used:

- `AXL`: Requires the ArchiveXL mod.
- `CDW`: Requires the Codeware mod.
- `CET`: Requires CyberEngine Tweaks mod.
- `EQEX`: Requires the Equipment EX mod.
- `NBVM`: Requires the No bags from Vending Machines mod.
- `NSU`: Requires the Native Settings UI mod.
- `RedEX`: Requires the RED4Ext mod.
- `RedSX`: Requires the RedScript mod.
- `TXL`: Requires the TweakXL mod.
- `VAT`: Requires the Virtual Atelier mod.
- `Vanilla`: Has no dependencies beyond the base game (all DLC is implied).

> NOTE: Markers do not include inherited mods. For example, a mod marked `EQEX` 
> will not include the mods that Equipment EX itself needs.

### Core level 1

These are mods that other mods depend on to work. They are sorted loosely by importance and usage area.
 
- [CyberEngine Tweaks][] aka `CET` - _Scripting framework for modders and quality of life fixes_
- [RED4ext][] aka `RedEX` - _Script extender for REDEngine 4_
- [RedScript][] aka `RedSC` - _Script compiler_
- [Codeware][] aka `CDW` - _Script extensions_
- [Archive XL][] aka `AXL` - _Load custom resources without touching original game files_
- [Tweak XL][] aka `TXL` - _TweakDB modifications loader and script extensions_
- [Mod Settings][] aka `ModSettings` - _Mod settings menu for RedScript mods_
- [Native Settings UI][] aka `NSU` - _Mod setting menus via the native UI_ `CET`
- [CookedApps Nulled][] - _Enable modding of NPC and Vehicle mesh files_ `Vanilla`
- [Material and Texture override][] - _Enables loading new materials_ `Vanilla`

### Core level 2

These are not required by any mods, but I consider them essential for any playthrough.

- [Custom Level Cap][] - _Change the level cap and starting attributes_ `CET` `NSU`
- [Fast Travel Anywhere][] - _Click and hold any map marker to travel there_ `CET`

### Core level 3

These are nice to have to improve aspects of the game.

- [Unequip Mods][] - _Allows unequipping weapon and clothing mods in the inventory_ `RedSC`
- [Blur Begone][] - _Removes blur on translucent objects_ `Vanilla`
- [Hide Read Shards][] - _Removes shards you have read from the world_ `RedSC`
- [Missing Persons - Hidden Gems][] - _Adds gigs to find all hidden gems in the game_ `CET` `NSU` `RedSC`
- [Real Vendor Names][] - _Display the actual vendor names for shop map markers_ `RedSC`
- [Simple Flashlight][] - `CET` `NSU`
- [Judy Romanced Enhanced][] - _Adds more romance options with Judy_ `Vanilla`
- [Panam Romanced Enhanced][] - _Adds more romance options with Panam_ `Vanilla`

### High Resolution textures

#### Requirements
 
- [No bags from vending machines][] aka `NBVM` - _Vending machines drop real items_ `CET`

#### Texture mods

- [CyberPunk HD reworked project](https://www.nexusmods.com/cyberpunk2077/mods/7652) _General texture improvements_ `Vanilla`
- [High Res containers](https://www.nexusmods.com/cyberpunk2077/mods/7998) _Containers: Boxes, vases, ..._ `Vanilla`
- [HQ Food - Soda - Real Chromanticore](https://www.nexusmods.com/cyberpunk2077/mods/8407) _Soda HD cans_ `NBVM`
- [HQ Food - Soda - Real NiCoLa](https://www.nexusmods.com/cyberpunk2077/mods/8491) _Soda HD cans_ `NBVM`
- [HQ Food and Drinks](https://www.nexusmods.com/cyberpunk2077/mods/7999) - _Food and drink items upscaled_ `Vanilla`
- [HQ NPCs - Johnny Silverhand](https://www.nexusmods.com/cyberpunk2077/mods/7168) `Vanilla`
- [HQ NPCs - Alt Conningham](https://www.nexusmods.com/cyberpunk2077/mods/7624) `Vanilla`
- [HQ NPCs - Kerry](https://www.nexusmods.com/cyberpunk2077/mods/7543) `Vanilla`
- [HQ NPCs - Misty](https://www.nexusmods.com/cyberpunk2077/mods/7817) `Vanilla`
- [HQ NPCs - Rogue](https://www.nexusmods.com/cyberpunk2077/mods/7545) `Vanilla`
- [HQ NPCs - Saul](https://www.nexusmods.com/cyberpunk2077/mods/7929) `Vanilla`
- [HQ NPCs - 8ug8ear](https://www.nexusmods.com/cyberpunk2077/mods/7167) `Vanilla`
- [HQ NPCs - Hanako](https://www.nexusmods.com/cyberpunk2077/mods/7542) `Vanilla`
- [HQ NPCs - Judy](https://www.nexusmods.com/cyberpunk2077/mods/7430) `Vanilla`
- [HQ NPCs - Panam](https://www.nexusmods.com/cyberpunk2077/mods/7171) `Vanilla`
- [HQ NPCs - Ripperdocs](https://www.nexusmods.com/cyberpunk2077/mods/7169) `Vanilla`
- [HQ NPCs - Takemura](https://www.nexusmods.com/cyberpunk2077/mods/7272) `Vanilla`
- [Environment Textures Overhaul](https://www.nexusmods.com/cyberpunk2077/mods/13372) - _General environment textures_ `Vanilla`
- [Improved Vegetation LODs](https://www.nexusmods.com/cyberpunk2077/mods/3627) _Improved level of detail_ `CDW` `ModSettings` `RedEX` `RedSC`
- [Trees and Vegetation](https://www.nexusmods.com/cyberpunk2077/mods/6093) - _High res trees and plants_ `Vanilla`
- [Joi Sky Advert](https://www.nexusmods.com/cyberpunk2077/mods/3837) - _Joi from Blade Runner_ `Vanilla`

### Photo mode mods

Photo mode is a great tool to capture game moments, so if you start spending more time in there
you may want to expand what you can do in there.

- [Appearance Menu Mod] aka `AMM` - _Feature-rich photo mode helper with props and actors_ `CET` `CDW`
- [Photo Mode Unlocker][] aka `PMU` - _Removes restrictions and adds new features_ `CET` `AXL` `TXL`
- [Wardrobe Anywhere][] - _Access the wardrobe anywhere with a custom hotkey_ `CET`
- [Character Customization Anywhere][] - _Open the character customization anywhere with a custom hotkey_ `CET`
- [Alternative Character Lighting][] - _Removes rim lighting from clothes and skin_ `Vanilla`
- [Facial Expressions Pack][] - _Adds lots of new facial expressions_ `TXL`
- [Portrait Enhancer][] - _Adds camera presets for portraits_ `Vanilla`
- [CharLi][] - _Character lighting suite_ `CET`
- [Action Pose Pack][] - _Adds some action poses for FemV_ `PMU` `RedEX`
- [Angy Pose Pack][] - _Collection of poses for FemV_ `AXL` `TXL`
- [Zwei Custom Poses - Core][] - _Collection of general purpose poses_ `PMU`
- [Zwei Custom Poses - Fashion][] - _Collection of poses for FemV_ `PMU`

### First Person fixes

First person view is pretty limited in the game. These mods make it possible to look down,
and see your body as you would in real life.

- [Immersive First Person][] - _Be able to see your body looking down_ `CET`
- [First Person Clothing fix][] - _Fix some first person view issues_ `Vanilla`
- [First Person Nude Fix][] _Fix breast in first person_ `Vanilla`

### Body mods

> NOTE: My personal preference is an improved vanilla body, so these mods
> are focused on this.

#### Body and skin

- [Unique Rig for V][] - _Allows a different body shape for V_ `Vanilla`
- [Morph Texture Removal][] - _Fixes head texture morphing_ `Vanilla`
- [Custom Breast Jiggle Physics][] - _Improved breast movement_ `Vanilla`
- [Ava - Body - Core][] - _Core body texture set_ `Vanilla`
- [Ava - Body - Option: Complexions][] - _Complexion textures_ `Vanilla`
- [Ava - Body - Option: Optional Better body with abs, 4K][] - _Body texture with abs_ `Vanilla`
- [Ava - Body - Option: Microdetails][] - _Better body details_ `Vanilla`
- [Ava - Skins - Core][] - _Core skin textures_ `Vanilla`
- [Ava - Skins - Option: Complexions][] - _Complexion textures_ `Vanilla`
- [Ava - Skins - Option: Microdetails][] - _Better skin details_ `Vanilla`
- [Ava - Skins - Option: Detailed Female NPCs][] - _Apply some skin improvements to female NPCs_ `Vanilla`

> NOTE: Ava's textures are all complementary, and can be used together in this selection.

#### Eyes

- [Unique Eyes Core](https://www.nexusmods.com/cyberpunk2077/mods/1937) - _Core mod for loading custom eye textures_ `Vanilla`
- [Kala's Eyes](https://www.nexusmods.com/cyberpunk2077/mods/3242) - _Selection of eye textures_ `Vanilla`

#### Hair

> NOTE: Modding hair in CyberPunk is somewhat clunky. There is a fixed amount of hair slots, so 
> hair modders choose which slots they want their hair to replace. It's important to keep track 
> of which mods use which slots to avoid conflicts (or at least to get the styles you want).

- [Preem Hair](https://www.nexusmods.com/cyberpunk2077/mods/8223) - _High res texture and more detailed strands_ `Vanilla`
- [Wingdeer Hair Collection](https://www.nexusmods.com/cyberpunk2077/mods/6072) - _The single largest selection_ `Vanilla`
- [Bayonetta 2](https://www.nexusmods.com/cyberpunk2077/mods/13409) - _Hair style frome the game "Bayonetta"_ `Vanilla`
- [Sori Yumi's Hairstyle Collection](https://www.nexusmods.com/cyberpunk2077/mods/2636) - _Selection of hair styles_ `Vanilla`

If you are a hair aficionado and are familiar with the PHP programming language, have a look 
at my [hair chooser tool](https://github.com/Mistralys/cyberpunk-hair-chooser). It can load hair styles from 
your installed mods, and lets you create a custom hair mod by choosing which style to use in which slots.

### Apparel mods

#### Prerequisites

- [Equipment EX][] aka `EQEX` - _Outfit manager and layered clothing slots_ `AXL` `TXL` `RedEX` `RedSC` `CDW`
- [Virtual Atelier][] aka `VAT` - _Buy clothes via virtual internet shops ingame_ `AXL` `CDW` `ModSettings` `RedEX` `RedSC`

> NOTE: For all atelier mods, the easiest way to see which mods are supported
is to browse through the author's mod list. This has the added benefit of showing
visual previews.

#### Adshield

- [Adshield store][] `VAT`

See [Adshield's mod list][] for compatible mods.

#### Alvarix

- [Alvarix Store][] `VAT`

See [Alvarix' mod list][] for compatible mods.

#### Nola Dreamer & Aquelyras

- [Nola Dreamer Store][] `VAT`
- [Nola Dreamer and Aquelyras Store][] `VAT`
- [Nola Dreamer and Veegee Store][] `VAT`

See [Nola Dreamer's mod list][] for compatible mods.

#### BeanCup

- [The Bean Cup Store][] - _Glasses_ `VAT`
- [The Bean Trunk Store][] - _Clothing_ `VAT`
- [The Bean Box Store][] - _Accessories and Jewelry_ `VAT`

See [BeanieBBY's mod list][] for compatible mods.

#### Complectedd

- [Necklace atelier](https://www.nexusmods.com/cyberpunk2077/mods/7016) _Necklaces_ `VAT`
  - [Alt Cunningham Chokers](https://www.nexusmods.com/cyberpunk2077/mods/6947)
  - [Alt's Necklaces](https://www.nexusmods.com/cyberpunk2077/mods/7122)
  - [Beaded Choker](https://www.nexusmods.com/cyberpunk2077/mods/6978)
  - [Long Spiked Choker](https://www.nexusmods.com/cyberpunk2077/mods/6996)

#### Cub

- [Cub Store](https://www.nexusmods.com/cyberpunk2077/mods/6949) _Clothing_ `VAT`
- [Cub's Closet Store](https://www.nexusmods.com/cyberpunk2077/mods/15621) _Clothing_ `VAT`

See [cubfan82's mod list](https://next.nexusmods.com/profile/cubfan82/mods?gameId=3333) for compatible mods.

#### Standalone

- [Atelier for Flash Posers][] `VAT`

### Vehicle Mods

#### Prerequisites

- [Virtual Car Dealer][] - _Enables buying vehicles via an ingame browser page_ `CDW` `AXL` `TXL` `RedEX` `RedSC`

#### Vehicles

- [Arcadia][] `VCD`
- [Ferrari Daytona SP3][] `VCD`
- [Audi R8][] `VCD`
- [Pagani Zonda Cinque][] `VCD`
- [Porsche 918 Spyder][] `VCD`
- [Mercedes One AMG][] `VCD`
- [Ford Mustang GT][] `VCD`

## Knowlege base

### Body mod: Solo Original

Can be found on the Nexus here: [KS Solo Body and Edgerunner Tats](https://www.nexusmods.com/cyberpunk2077/mods/4813)

Issue: the mod does not want to be loaded from Vortex' `Cyberpunk 2077/mods` folder when installing via Vortex.

1. Install via Vortex
2. Open the game mods folder after deploying
3. Copy the `.archive` file to `Cyberpunk 2077/archive/pc/mod`

> NOTE: Leave the Vortex folder intact, that way it stays visible.
> Best to add a note to remember to remove the archive manually
> on uninstall.

[Archive XL]: https://www.nexusmods.com/cyberpunk2077/mods/4198
[Codeware]: https://www.nexusmods.com/cyberpunk2077/mods/7780
[CookedApps Nulled]: https://www.nexusmods.com/cyberpunk2077/mods/3051
[CyberEngine Tweaks]: https://www.nexusmods.com/cyberpunk2077/mods/107
[Material and Texture override]: https://www.nexusmods.com/cyberpunk2077/mods/5266
[Mod Settings]: https://www.nexusmods.com/cyberpunk2077/mods/4885
[Native Settings UI]: https://www.nexusmods.com/cyberpunk2077/mods/3518
[RED4Ext]: https://www.nexusmods.com/cyberpunk2077/mods/2380
[RedScript]: https://www.nexusmods.com/cyberpunk2077/mods/1511
[Tweak XL]: https://www.nexusmods.com/cyberpunk2077/mods/4197
[Custom Level Cap]: https://www.nexusmods.com/cyberpunk2077/mods/2909
[Fast Travel Anywhere]: https://www.nexusmods.com/cyberpunk2077/mods/1943
[Photo Mode Unlocker]: https://www.nexusmods.com/cyberpunk2077/mods/4319
[Unequip Mods]: https://www.nexusmods.com/cyberpunk2077/mods/2358
[Wardrobe Anywhere]: https://www.nexusmods.com/cyberpunk2077/mods/5145
[Appearance Menu Mod]: https://www.nexusmods.com/cyberpunk2077/mods/790
[Blur Begone]: https://www.nexusmods.com/cyberpunk2077/mods/8105
[Character Customization Anywhere]: https://www.nexusmods.com/cyberpunk2077/mods/3930
[Equipment EX]: https://www.nexusmods.com/cyberpunk2077/mods/6945
[Hide Read Shards]: https://www.nexusmods.com/cyberpunk2077/mods/2820
[Immersive First Person]: https://www.nexusmods.com/cyberpunk2077/mods/2675
[Real Vendor Names]: https://www.nexusmods.com/cyberpunk2077/mods/4941
[Simple Flashlight]: https://www.nexusmods.com/cyberpunk2077/mods/2913
[Missing Persons - Hidden Gems]: https://www.nexusmods.com/cyberpunk2077/mods/5058
[Facial Expressions Pack]: https://www.nexusmods.com/cyberpunk2077/mods/7912
[Portrait Enhancer]: https://www.nexusmods.com/cyberpunk2077/mods/8237
[CharLi]: https://www.nexusmods.com/cyberpunk2077/mods/8176
[Action Pose Pack]: https://www.nexusmods.com/cyberpunk2077/mods/8698
[Angy Pose Pack]: https://www.nexusmods.com/cyberpunk2077/mods/6871
[Zwei Custom Poses - Core]: https://www.nexusmods.com/cyberpunk2077/mods/7165
[Zwei Custom Poses - Fashion]: https://www.nexusmods.com/cyberpunk2077/mods/7156
[First Person Clothing Fix]: https://www.nexusmods.com/cyberpunk2077/mods/4862
[First Person Nude Fix]: https://www.nexusmods.com/cyberpunk2077/mods/3620
[Judy Romanced Enhanced]: https://www.nexusmods.com/cyberpunk2077/mods/4508
[Panam Romanced Enhanced]: https://www.nexusmods.com/cyberpunk2077/mods/4626
[No bags from vending machines]: https://www.nexusmods.com/cyberpunk2077/mods/8387
[Alternative Character Lighting]: https://www.nexusmods.com/cyberpunk2077/mods/237

[Unique Rig for V]: https://www.nexusmods.com/cyberpunk2077/mods/3725
[Morph Texture Removal]: https://www.nexusmods.com/cyberpunk2077/mods/2419
[Custom Breast Jiggle Physics]: https://www.nexusmods.com/cyberpunk2077/mods/3665
[Ava - Body - Core]: https://www.nexusmods.com/cyberpunk2077/mods/1873
[Ava - Body - Option: Complexions]: https://www.nexusmods.com/cyberpunk2077/mods/1873?tab=files
[Ava - Body - Option: Optional Better body with abs, 4K]: https://www.nexusmods.com/cyberpunk2077/mods/1873?tab=files
[Ava - Body - Option: Microdetails]: https://www.nexusmods.com/cyberpunk2077/mods/1873?tab=files
[Ava - Skins - Core]: https://www.nexusmods.com/cyberpunk2077/mods/11937
[Ava - Skins - Option: Complexions]: https://www.nexusmods.com/cyberpunk2077/mods/11937?tab=files
[Ava - Skins - Option: Microdetails]: https://www.nexusmods.com/cyberpunk2077/mods/11937?tab=files
[Ava - Skins - Option: Detailed Female NPCs]: https://www.nexusmods.com/cyberpunk2077/mods/11937?tab=files

[Virtual Atelier]: https://www.nexusmods.com/cyberpunk2077/mods/2987
[Alvarix Store]: https://www.nexusmods.com/cyberpunk2077/mods/4602
[Adshield Store]: https://www.nexusmods.com/cyberpunk2077/mods/8452
[Nola Dreamer And Aquelyras Store]: https://www.nexusmods.com/cyberpunk2077/mods/8702
[Nola Dreamer and Veegee Store]: https://www.nexusmods.com/cyberpunk2077/mods/11964
[Nola Dreamer Store]: https://www.nexusmods.com/cyberpunk2077/mods/5114
[Nola Dreamer's mod list]: https://next.nexusmods.com/profile/NolaDreamer/mods?gameId=33331
[Alvarix' mod list]: https://next.nexusmods.com/profile/AlvarixPT/mods?gameId=3333
[Adshield's mod list]: https://next.nexusmods.com/profile/Adshield/mods?gameId=3333
[Atelier for Flash Posers]: https://www.nexusmods.com/cyberpunk2077/mods/8886
[The Bean Cup Store]: https://www.nexusmods.com/cyberpunk2077/mods/12223
[The Bean Box Store]: https://www.nexusmods.com/cyberpunk2077/mods/12765
[The Bean Trunk Store]: https://www.nexusmods.com/cyberpunk2077/mods/12836
[BeanieBBY's mod list]: https://next.nexusmods.com/profile/beaniebby/mods?gameId=3333

[Virtual Car Dealer]: https://www.nexusmods.com/cyberpunk2077/mods/4454
[Arcadia]: https://www.nexusmods.com/cyberpunk2077/mods/3403
[Ferrari Daytona SP3]: https://www.nexusmods.com/cyberpunk2077/mods/13465
[Audi R8]: https://www.nexusmods.com/cyberpunk2077/mods/8827
[Pagani Zonda Cinque]: https://www.nexusmods.com/cyberpunk2077/mods/8795
[Porsche 918 Spyder]: https://www.nexusmods.com/cyberpunk2077/mods/9125
[Mercedes One AMG]: https://www.nexusmods.com/cyberpunk2077/mods/13502
[Ford Mustang GT]: https://www.nexusmods.com/cyberpunk2077/mods/13248
