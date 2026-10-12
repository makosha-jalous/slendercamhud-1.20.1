# Slender Camera — migration draft for Minecraft 1.20.1

Target: Minecraft Java Edition 1.20.1, Forge 47.2.0, Java 17.

Changes in this draft:
- Updated ForgeGradle, Minecraft mappings and Forge dependency to 1.20.1.
- Updated mods.toml loader/Minecraft version ranges.
- Migrated the HUD overlay callback to GuiGraphics and the matrix import to JOML.
- Replaced removed Item.Properties.tab(...) usage with a registered creative tab.
- Updated SoundEvent construction to createVariableRangeEvent.

Important: this draft has not been compiled or launched in a Minecraft/Forge environment here. Build and in-game testing are still required. The project archive did not contain Gradle wrapper scripts, so run it using an installed compatible Gradle or add the wrapper from the Forge 1.20.1 MDK.
