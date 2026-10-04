# Redstone Scanner (Fabric, Minecraft 26.2)

Client-side mod. Scans loaded chunks within 150 blocks for repeaters, comparators,
redstone dust, observers and crafters, groups them per chunk, and lists hotspots on the HUD.

Keys: R = toggle, V = cycle minimum components per chunk.
Requires: Fabric Loader 0.19.3+, Fabric API 0.159.0+26.2 (or newer 26.2 build), Java 25.

## Build
1. Install JDK 25 and Gradle 9.4+.
2. In this folder run:  gradle wrapper --gradle-version latest
3. Then:               ./gradlew build        (Windows: gradlew.bat build)
4. Jar is in build/libs/redstonescanner-1.0.0.jar  (NOT the -sources jar)

## Install in Modrinth App
Create/open a Fabric 26.2 profile -> Add content -> install "Fabric API" from Modrinth
-> open the profile's mods folder (profile page > ... > Open folder > mods) and drop the jar in.
