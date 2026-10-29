# HappyMonk3y's Tier Tagger

A Fabric client mod using the MCTiers v2 API. Includes compact tier badges in player nametags and the tab list, Classic and MCTiers icon options, customizable tier colors, Mod Menu settings, and `/tiers <player>` search.

## Source

The complete, buildable source for each release is included in the source ZIP files in this repository. Download and extract the ZIP before building. Each archive contains the Java source, resources, tests, Gradle wrapper, API contract, and license notices. Minecraft game files, Gradle caches, local settings, and credentials are not included.

- [Version 1.6.0 source for Minecraft 1.21.11](happymonk3ys-tier-tagger-1.6.0-source.zip)

For 1.6.0, use Java 21 and run `./gradlew build` (`gradlew.bat build` on Windows). Fabric API and Mod Menu are required at runtime.

## Custom display

This custom edition displays HappyMonk3y as retired LT2 in Crystal and LT3 in the other gamemodes. This is a local cosmetic override, not a change to official MCTiers rankings. The default retired color is `#8FB6DC`.

## License and credits

The combined distribution is licensed under **GPL-3.0-only**. Classic and MCTiers mode icons come from [PvPTiers/Tiers](https://github.com/PvPTiers/Tiers). See [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt) for the exact revision and attribution. Independently authored code and the original fallback/app icon are additionally available under [MIT](LICENSE-MIT.txt).

This project is not endorsed by MCTiers, PvPTiers, Mojang, or Microsoft.
