# Changelog

## 1.21+2.0

Added lots of mods I cannot keep track of, please refer to the description page on Modrinth or Github to see full list of mods.

### Known Issues

- As of Lithium 0.13.0, explosion optimisation is incompatible with carpet (https://github.com/CaffeineMC/lithium-fabric/issues/543). A workaround to disable the optimisation is found in `config/lithium.properties` with the line `mixin.world.explosions.cache_exposure=false`. When migrating config folder, make sure to not overwrite the existing workaround, or make sure to add it back in after migration. Users may attempt to remove the workaround if new updates from either Lithium or Carpet addresses the issue.
- Carpet AMS was causing crashes with Carpet TIS, a recent update of Carpet TIS fixes some issues, but I have yet to test Carpet AMS

### Notes

- Ryoamic Lights is used in place of LambDynamicLights 1.21 port
- Nvidium is a Nvidia GPU-specific Sodium enhancement for higher fps (16xx series or newer). The mod should disable itself on non-Nvidia systems and when using Iris. Tested and works on a RTX20xx platform. Disable this mod if you suspect it causing issues on your system.
- Syncmatica is not yet available on Modrinth
- Newest Carpet version is still only available on Curseforge

### Planned Mods

- Antighost has 1.21 but currently crashes (https://github.com/IkyMax/AntiGhost/issues/2), a fix for it was uploaded to Modrinth which for some reason requires crowdin-translate dependency which is unmaintained for a very long time, therefore it's not included.
- Nvidium and More Culling is temporarily removed, being incompatible with sodium 0.6.0 beta
- Controversial mods that some may consider cheating, such as Bedrock Miner or Baritone
