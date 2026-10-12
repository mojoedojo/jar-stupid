# MCA Village Titles (Forge 1.20.1)

Shows a Traveler's Titles-style banner when you walk into an MCA village:

    ✦ NEW SETTLEMENT ✦
    Willowbrook
    A Village in the Overworld

* Uses MCA's village data (`VillageManager`), so the name is whatever MCA has (including renames).
* Separate overlay from Traveler's Titles; moves down automatically if Traveler's Titles is installed.
* Install on client AND server (server detects the village, client draws it). Works in single player too.
* Built against MCA 7.7.1-beta.4 (the merged Forge/Fabric jar; its Forge classes are under `forge.net.conczin...`).

## Build
    gradle wrapper   # once, if you don't have a wrapper
    ./gradlew build  # jar -> build/libs/
Needs Java 17 and internet access to maven.minecraftforge.net.
