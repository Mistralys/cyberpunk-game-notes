# Cyberpunk Game Notes

Modding notes for Cyberpunk 2077

## Mod list

I have recently built a [Vortex mod list exporter][] for my personal way of
tagging mods by renaming them in Vortex. Thanks to this, I now have several 
helpful documents to keep track of my mods:

- [List of mods, categorized](./modlist/cyberpunk2077-mods.md)
- [List of tags and related mods](./modlist/cyberpunk2077-tags.md)
- [Mod details JSON file](./modlist/cyberpunk2077-modlist.json)

## Body mods at a glance

> NOTE: The texture framework used by a body mod is shown in parentheses.
> Have a look at the [RedModding wiki on texture frameworks][] for more information.

- [Enhanced Big Breasts Body](https://www.nexusmods.com/cyberpunk2077/mods/4654) aka Hyst Body (VTK Framework)
- [KS Solo Body](https://www.nexusmods.com/cyberpunk2077/mods/4813) (UV Framework)
- [Lush Body](https://www.nexusmods.com/cyberpunk2077/mods/4901) (UV Framework)
- [Spawn0 Body](https://www.nexusmods.com/cyberpunk2077/mods/1424) (Spawn0 Framework)
- [VTK Body](https://www.nexusmods.com/cyberpunk2077/mods/7054) (VTK Framework)
- [UV Framework](https://www.nexusmods.com/cyberpunk2077/mods/3783)

## Hair mods

Modding hair in CyberPunk is somewhat clunky. There is a fixed number of hair slots, so 
hair modders choose which slots they want their hair to replace. It's important to keep track 
of which mods use which slots to avoid conflicts (or at least to get the styles you want).

- [Preem Hair](https://www.nexusmods.com/cyberpunk2077/mods/8223) - _High res texture and more detailed strands_ `Vanilla`
- [Wingdeer Hair Collection](https://www.nexusmods.com/cyberpunk2077/mods/6072) - _The single largest selection_ `Vanilla`
- [Bayonetta 2](https://www.nexusmods.com/cyberpunk2077/mods/13409) - _Hairstyle from the game "Bayonetta"_ `Vanilla`
- [Sori Yumi's Hairstyle Collection](https://www.nexusmods.com/cyberpunk2077/mods/2636) - _Selection of hair styles_ `Vanilla`

If you are a hair aficionado and are familiar with the PHP programming language, have a look 
at my [hair chooser tool](https://github.com/Mistralys/cyberpunk-hair-chooser). It can load hairstyles from 
your installed mods, and lets you create a custom hair mod by choosing which style to use in which slots.

## Knowlege base

### Body mod: Solo Original

Can be found on the Nexus here: [KS Solo Body and Edgerunner Tats](https://www.nexusmods.com/cyberpunk2077/mods/4813)

Issue: the mod does not want to be loaded from Vortex' `Cyberpunk 2077/mods` folder when installing via Vortex.

1. Install via Vortex
2. Open the game mods folder after deploying
3. Copy the `.archive` file to `Cyberpunk 2077/archive/pc/mod`

> NOTE: Leave the Vortex folder intact, that way it stays visible.
> Best to add a note to remember to remove the archive manually
> on uninstallation.

[RedModding wiki on texture frameworks]: https://wiki.redmodding.org/cyberpunk-2077-modding/modding-guides/npcs/custom-tattoos-and-scars/converting-between-tattoo-frameworks#the-unique-v-texture-framework
[Vortex mod list exporter]: https://github.com/Mistralys/vortex-modlist-exporter
