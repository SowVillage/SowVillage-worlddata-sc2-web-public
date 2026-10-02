# Minecraft textures

The selected block textures are from Mojang's official [Bedrock samples](https://github.com/Mojang/bedrock-samples), revision `46ba6ea985fb5a92d79a9419198f10dda14c199d`.

Copyright Mojang AB. These resources are provided subject to the [Minecraft End User License Agreement](https://www.minecraft.net/en-us/eula). The repository's original notice is preserved in `MOJANG-LICENSE.md`. They are not represented as MIT-licensed or public-domain artwork.

This viewer uses only textures referenced by the archived world's real block palette. A generated 16-pixel atlas combines those files, adds a one-pixel border, applies a fixed foliage/water color, and selects the first frame of animated textures. Source files, their exact URLs, sizes and SHA-256 checksums are retained in the offline `SowVillage-worlddata-sc2-workbench/assets/bedrock-samples/sources.json`; the public data repository contains only serving assets and attribution.

The material mapping preserves legacy wall variants and resolves directional faces from the archived block states. Direction values follow Microsoft's [official block state reference](https://learn.microsoft.com/en-us/minecraft/creator/reference/content/blockreference/examples/blockstateandtraitlistings?view=minecraft-bedrock-stable). Six additional textures from the same pinned Mojang revision represent open barrels, full bee nests and beehives, powered observers, sticky piston heads, and lit pumpkins. Existing atlas tile numbers are preserved; the extra textures occupy previously unused tiles.

This is an independent community archive viewer. Minecraft and its assets belong to Mojang/Microsoft.
