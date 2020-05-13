# 1.15.2 Modding Project (Buzzy Brocade)

-- begun: 18 Jan 2020

-- last updated: 29 Feb 2020

-- by: ArahirXVII

*This project is built on Fabric using MultiMC.*

**`Fabric`** `0.7.8+build.184`

**Purpose**: I wanted to add some mods to 1.15.2

#### Useful Seeds

`4605881693702610778`

`-8666948920454124715` climatic. plains village spawn.

## ToDo
- [ ] Is Trident Fixer needed with Aquarius?

## Mods

### Core
|Name|Purpose|Component|Version|Dependencies|Dependents|Server/Client|
|-|-|-|-|-|-|-|
|[Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api/files) |||0.4.32+build.292-1.15|
|[Cotton](https://www.curseforge.com/minecraft/mc-mods/cotton/files) |||1.0.2||Epicurean, Toolbuilder||
|[nbt Crafting](https://www.curseforge.com/minecraft/mc-mods/nbt-crafting/files) |required for Simply Enchanted||1.2.14+1.15.1|Fabric API, REI||server,optional on client|
|[Reborn Core](https://www.curseforge.com/minecraft/mc-mods/reborncore/files) |for tech reborn||1.15-4.2.3+build.99|
|[MaLiLib](https://www.curseforge.com/minecraft/mc-mods/malilib/files) |library||1.15.2-0.10.0-dev.20+arne.2|||client|
|[Phosphor](https://www.curseforge.com/minecraft/mc-mods/phosphor/files) |huge improvements to tick speed, chunk loading due to lighting improvements||0.3.6|||client optional, server optional|
|[Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium/files) |performance server and client||0.3.2|||client optional, server optional|
|[Fabric Language Kotlin](https://www.curseforge.com/minecraft/mc-mods/fabric-language-kotlin/files) |||1.3.61 build 2||Clipboards, Stockpile||
|[TooManyCrashes](https://www.curseforge.com/minecraft/mc-mods/toomanycrashes/files) |Crash Reporting||1.0|


### Biomes /Worldgen
|Name|Purpose|Component|Version|Dependencies|Server/Client|
|-|-|-|-|-|-|
|[Traverse](https://www.curseforge.com/minecraft/mc-mods/traverse/files) |13 new biomes mostly vanilla+ in nature|biomes|2.1.9+build.17|
|[Terrestria](https://www.curseforge.com/minecraft/mc-mods/terrestria/files) |12 more mods|biomes|1.2.1+build.29|
|[Climatic World Type](https://www.curseforge.com/minecraft/mc-mods/climatic-world-type/files) |places biomes based on climatic features|biomes, worldgen|1.1.4|
|[Wild World](https://www.curseforge.com/minecraft/mc-mods/wild-world/files) |stalagmites, skulls, mushrooms, icicles, leafpiles, wild crops||1.2.0+1.15|
|[BetterNether](https://www.curseforge.com/minecraft/mc-mods/betternether/files) |lots of content to Nether|nether worldgen|2.5.1|

### Utilities

|Name|Purpose|Component|Version|Dependencies|Server/Client|
|-|-|-|-|-|-|
|[Light Overlay](https://www.curseforge.com/minecraft/mc-mods/light-overlay/files) |Mob spawn points|lighting|4.2|Fabric API|client only|
|[Diggus Maximus](https://www.curseforge.com/minecraft/mc-mods/diggus-maximus/files) |ore excavator|mining|1.2.6||server,client|
|[Leaf Decay](https://www.curseforge.com/minecraft/mc-mods/leaf-decay/files) |fast leaf decay||19w46b-1.1.1|Fabric API||
|[Roughly Enough Items](https://www.curseforge.com/minecraft/mc-mods/roughly-enough-items/files) |REI|inventory|3.5.4|Fabric API||
|[Hwyla](https://www.curseforge.com/minecraft/mc-mods/hwyla/files) |||1.15.2-1.9.20-71|Fabric API||
|[Inventory Sorter](https://www.curseforge.com/minecraft/mc-mods/inventory-sorting/files) ||inventory|1.6.3|Fabric API|client,server|
|[NBT Tooltip](https://www.curseforge.com/minecraft/mc-mods/nbt-tooltip/files) |shows nbt info in tooltip|Tooltip|1.14-1.0.3|Fabric API|client|
|[VoxelMap](https://www.curseforge.com/minecraft/mc-mods/voxelmap/files) |minimap||1.9.14|Fabric API|client|
|[Enchanted ToolTips](https://www.curseforge.com/minecraft/mc-mods/enchanted-tooltips/files)|enchantment info in tooltips|Tooltip|1.2.4||client|
|[Modded Tool Tips](https://www.curseforge.com/minecraft/mc-mods/modded-tool-tips/files) |displays mod in tooltip|Tooltip|1.1.1|
|[Tooltip Autowrap](https://www.curseforge.com/minecraft/mc-mods/tooltip-autowrap/files) |wraps long tooltips|Tooltip|1.0.2|
|[Vanilla Death Chest](https://www.curseforge.com/minecraft/mc-mods/vanilladeathchest/files) |||1.15.2-1.10.3.5-Fabric|
|[SimpleHarvest](https://www.curseforge.com/minecraft/mc-mods/simpleharvest/files) |right click harvest||1.0.4||server|
|[Iron Barrels](https://www.curseforge.com/minecraft/mc-mods/iron-barrels/files) |Storage||2.2.1|
|[Resource Melons](https://www.curseforge.com/minecraft/mc-mods/resource-melons/files) |melons that grow resources||1.3.0|
|[MiniHUD](https://www.curseforge.com/minecraft/mc-mods/minihud/files) |HUD||1.15.2-0.19.0|MaLiLib|client|
|[Litematica](https://www.curseforge.com/minecraft/mc-mods/litematica/files) |building helper, schematics||1.15.2-0.0.0|MaLiLib|client|
|[Tweakeroo](https://www.curseforge.com/minecraft/mc-mods/tweakeroo/files) |various tweaks||1.15.2-0.10.0|
|[MAmbience](https://www.curseforge.com/minecraft/mc-mods/mambience/files) |dynamic sounds|utilities|1.0.0+1.14|Fabric API|client, optional server|
|[Stockpile](https://www.curseforge.com/minecraft/mc-mods/stockpile/files) |storage||1.1.3+1.15.1|
|[Beenfo](https://www.curseforge.com/minecraft/mc-mods/beenfo/files) |Bee info|tooltips|1.15fabric0.4.23-1.0.3|
|[Horse Stats Vanilla](https://www.curseforge.com/minecraft/mc-mods/horsestatsvanilla/files) |horse stats in the horse inventory|tooltips|1.0.5|
|[Epicurean](https://www.curseforge.com/minecraft/mc-mods/epicurean/files) |||2.2.4+1.15.2|
|[Experience Container](https://www.curseforge.com/minecraft/mc-mods/experience-container/files) |box for xp||1.5|
|[Fabriblocks](https://www.curseforge.com/minecraft/mc-mods/fabriblocks/files) |building blocks||1.1.7|
|[Redstone Bits](https://www.curseforge.com/minecraft/mc-mods/redstone-bits/files) |Placer, Breaker, Checker blocks|Redstone|1.2.2|
|[Uncraft Me](https://www.curseforge.com/minecraft/mc-mods/uncraft-me/files) |uncraft Netherwart and Quartz blocks||0.1|
|[Extra Bows](https://www.curseforge.com/minecraft/mc-mods/extra-bows/files) |Upgradeable Bows, arrows|Archery|1.15.2 Fabric b2|
|[Easy Feeding (Easy Feed and Breed)](https://www.curseforge.com/minecraft/mc-mods/easy-feed/files) |Breeding|Allows breeding of animals by throwing food on the ground|1.0.0|
|[Building Wands](https://www.curseforge.com/minecraft/mc-mods/building-wands/files) |builder's wands|building|1.0.9|
|[Clipboards](https://www.curseforge.com/minecraft/mc-mods/clipboards/files) |notes and todo lists|writing|1.0.0+1.15.2|||crash sometimes on multiple pages|
|[Roughly Enough Resources](https://www.curseforge.com/minecraft/mc-mods/roughly-enough-resources/files) |oregen charts in REI|inventory|1.3.2||server and client|
|[Fabric Controlling](https://www.curseforge.com/minecraft/mc-mods/fabric-controlling/files) |search bar for keybinds|keybinds controls|1.0.3|
|[WorldEdit](https://www.curseforge.com/minecraft/mc-mods/worldedit/files) |world editor|world edit|7.1.0|
|[Mod Menu](https://www.curseforge.com/minecraft/mc-mods/modmenu/files) |mod menu|mod list|1.10.2||client,server optional|
|[Inventory Profiles](https://www.curseforge.com/minecraft/mc-mods/inventory-profiles/files) |Inventory sorting|Inventory|0.2.0||client|


### Enchanting

|Name|Purpose|Component|Version|Dependencies|Server/Client|
|-|-|-|-|-|-|
|[AnvilFix](https://www.curseforge.com/minecraft/mc-mods/anvil-fix/files) |removes xp level limit on anvils|XP|1.1.2|
|[Better Than Mending](https://www.curseforge.com/minecraft/mc-mods/better-than-mending/files) |sneak-right-click a Mending item to repair it with xp|Mending|1.1.1|
|[Mend Trend](https://www.curseforge.com/minecraft/mc-mods/mend-trend/files) |Mending from enchanting tables|Mending|1.0.2|
|[Smarter Mending](https://www.curseforge.com/minecraft/mc-mods/smarter-mending/files) |mending least durability item between hands|Mending|1.1.0|
|[Stackable Damage Enchants](https://www.curseforge.com/minecraft/mc-mods/stackable-damage-enchants/files) |stacks damage on swords etc|Stacking|1.0.1|
|[Protection Renewal](https://www.curseforge.com/minecraft/mc-mods/protection-renewal/files) |stacks prot enchant on armor|Stacking|1.0.1|
|[Simply Enchanted](https://www.curseforge.com/minecraft/mc-mods/simply-enchanted/files) |specific enchants|1.0.6|

### Mechanics

|Name|Purpose|Component|Version|Dependencies|Server/Client|
|-|-|-|-|-|-|
|[Aquarius](https://www.curseforge.com/minecraft/mc-mods/aquarius/files) |channeling, flippers, prismarine rods, chorus conduits, guardian sight|Water|1.4.0+1.15|
|[Autofish](https://www.curseforge.com/minecraft/mc-mods/autofish/files) |recasts rod|Fishing|0.8.5|
|[Tool Builder](https://www.curseforge.com/minecraft/mc-mods/tool-builder/files) |craftable tools from multiple materials|Tools & Armor|2.0.2|
|[Vanilla Toolsets](https://www.curseforge.com/minecraft/mc-mods/vanilla-toolsets/files) |new tools and armor|Tools & Armor|1.2.2|
|[Amethyst Mod (Fabric)](https://www.curseforge.com/minecraft/mc-mods/amethyst-mod-fabric/files) |amethysts, tools, armor|Tools & Armor|1.2.1|
|[Trident Fixer](https://www.curseforge.com/minecraft/mc-mods/trident-fixer/files) |repairable tridents, does Aquarius already do this?|Tools & Armor|1.0.0|
|[Silky Spawners](https://www.curseforge.com/minecraft/mc-mods/silky-spawners/files) |silk touch spawners|Spawners|1.0.2|
|[Smooth Bedrock](https://www.curseforge.com/minecraft/mc-mods/blayykes-smooth-bedrock/files) |World Gen||1.1.4|
|[Soul Shards Respawn](https://www.curseforge.com/minecraft/mc-mods/soul-shards-respawn/files) |ability to build spawners||fabric-1.15.2-1.2.0-15|
|[Infinity Fix](https://www.curseforge.com/minecraft/mc-mods/infinity-fix/files) |Allows Infinity and Mending to be applied together, infinity crossbow||1.1.0|
|[Tech Reborn](https://www.curseforge.com/minecraft/mc-mods/techreborn/files) |tech||1.15-3.3.4+build.189|


### Didn't Work
|Name|Purpose|Component|Version|Dependencies|Server/Client|
|-|-|-|-|-|-|
|[Lettuce Not Crash](https://www.curseforge.com/minecraft/mc-mods/lettuce-not-crash/files) |Removes corrupted Block entities||1.0|crashed|
|[Optifabric](https://www.curseforge.com/minecraft/mc-mods/optifabric) |||1.0.0-beta4|crashed|
|[Optifine](https://optifine.net/downloads) |||1.15.2 HD_U_G1_pre5|crashed|
|[Optifine](https://optifine.net/downloads) |||1.14.4 HD_U_F5|incompatable version|
|[Optifine](https://optifine.net/downloads) |||1.15.2 HD_U_G1_pre7|crashed||
|[Better Foliage](https://www.curseforge.com/minecraft/mc-mods/better-foliage) |||2.5.0+4c439dc-Fabric-1.14.4|requires 1.14.2|
|[Nether things](https://www.curseforge.com/minecraft/mc-mods/nether-things) |||1.2.0|crashed|
|[Cotton Resources](https://www.curseforge.com/minecraft/mc-mods/cotton-resources) |||1.4.1|
|[Extra Pieces](https://www.curseforge.com/minecraft/mc-mods/extra-pieces) |||2.8.3|
|[Jankson](https://www.curseforge.com/minecraft/mc-mods/jankson) |library||1.0.0+j1.1.2|
|[PlayerGraves](https://www.curseforge.com/minecraft/mc-mods/player-graves/files) |||1.0.0_1.14|crash|
|[Death Bags for Fabric](https://www.curseforge.com/minecraft/mc-mods/death-bags-for-fabric/files) |Death bag||1.14.3-5.6-FABRIC|bag doubles items on death|
|[More Enchantments](https://www.curseforge.com/minecraft/mc-mods/fabric-more-enchantments) |Veining, Timber, Alpha Fire, Familiarity, Curse of the End, Imbued, Soulbound, Chaos, Curse of the Trooper, Marksman|Enchants|1.9.6|breaks with Vanilla Death Chest|
|[Mpcs's Backpacks](https://www.curseforge.com/minecraft/mc-mods/mpcs-backpacks/files) |backpacks|storage|1.1.5|crashes on opening backpack|
