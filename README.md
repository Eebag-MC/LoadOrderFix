This mod contains **no actual content**, it acts as a load re-ordering for the mods [Ad Astra](https://www.curseforge.com/minecraft/mc-mods/ad-astra) and [Gregtech CEu Modern](https://www.curseforge.com/minecraft/mc-mods/gregtechceu-modern) using Forge's built in mod loading system.

**Built to work with Gregtech Modern 7.5.3 and Ad Astra 1.15.21**


The `mods.toml`contains the following:
```
[[dependencies.loadorderfix]]
    modId="ad_astra"
    mandatory=false
    versionRange="[0,)"
    ordering="AFTER"
    side="BOTH"

[[dependencies.loadorderfix]]
    modId="gtceu"
    mandatory=false
    versionRange="[0,)"
    ordering="BEFORE"
    side="BOTH"
```


Related GT Git issue: [#5699](https://github.com/GregTechCEu/GregTech-Modern/issues/5699)