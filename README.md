<img src="https://elytrium.net/src/img/elytrium.webp" alt="Elytrium" align="right">

# LimboAPI

[![Join our Discord](https://img.shields.io/discord/775778822334709780.svg?logo=discord&label=Discord)](https://ely.su/discord)
![Modrinth Game Versions](https://img.shields.io/modrinth/game-versions/TZOteSf2?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAIkAAAA8CAMAAABl%2FWk9AAABAlBMVEUAAAAApcwAqM4Apc4Ap88Apc4Apc4AqM0Aps0Ap84Apc0ApswApc4Aps0Ap80Aps4Ap80Aps0Ap84Aps0Aps4Aps0EqdAHrNMKrtQNsdcRtNoVttwWtt0buuAbuuAbuuAauuAbuuEauuAbu%2BAbuuAbuuEbu%2BAbuuEau%2BAbuuAbuuEau%2BEauuAbuuAbueAbuuAau%2BEbuuAauuAauuAbuuEauuEau%2BAbuuAau%2BEbu%2BAWtt0bvOAau%2BEZuOEYt94cvOEUtt8YudsVsdYAn90A%2F%2F8CqM8Ap84Bp84Aps0Ap80Aps0Aps0Aps0auuAauuAbuuAbuuAauuAauuAbuuAAps0buuCTPBtaAAAAVHRSTlMAIhwzOj5ESk1aZnB3f4iTnKWqrrW7xMDCxdDa3%2BDc2tbMxcC8uLOvp6KflpCHgXl1b15ZVE5EQDovKSQhHRcRDAgFAgHL1Nne5e30%2FPj08e3q5vwu6%2BLEAAADTUlEQVR42sXXhXLDPAzAcY2ZGcrMzAzjYhK9%2F6N8YA8zW62Xwu9gvOp6yt8JTKmSjXnHA18Jlqn63xAj5IbLGqWWi%2FvH%2BJ2jufwh3oUXPYSGMmlYjFLcN0aRkc%2BJzKACi5DUUSzQBMj22aeuNsxfUTaIjS1qBJkozF3XRS9HBrkczFsGJVwd9vMEcqMazFfLhhIF9vO2Hd%2B5T05n4GAVJJIoEQAmhZ%2BujFl4lYxSH6KYXmY%2Fb4y%2BfevBmIVDEIqiRFTw8%2FGrMQMnIFLuo9iwzg%2FCnz%2B%2F7RnW7YFIACWSwASRm%2BGqXLZAoIASthaPHprojwbh7Xh%2Fkr3NtlrUMsC40UwjVuW1DH%2BVlkaty36exd9uDKn9OUStyKPmQBN6VbbgrxIToybSf5rle0JHrV%2F5iJrQ%2FZtsT1bgbyJTRU1lVd6OdoV23kdc2dnoqkRNa3xETebSUNRjNdvrGcaFoCZ%2BFBsVP6ImNXhRHmUVYKVnWiYyarozVgemioRrQ9U2wA775BxMOr%2Bj5gimCk34kELCnaFqDWCdfXJER80eTLIhvokh4dZQwt%2BJ7jm%2FvoRR40PkG3R%2F6ZXtPV5McrbXZqXcOz1aEUdtGONDiNQHKHXPdo97WQPOStSGJeUCcw%2BzSPz3aEXgt2atBVzHO82W9NpgCX8ATpiGKKaCDh37%2FjIwdQ2F9B8HTx0s4Tvg%2Bz5EyKnjuyFvWzevTxH7Q7DEh0yyYx6C0%2BrAxKYJ7PHGyh%2B1AKDUR8bm5UOYefnjX9tN3J9Y1ztpAiSRlgCmNkKz8ZsxO0cAXT%2BS9CIwOSpq1r3wC4NkawATIaJm3TM7i3Uk%2Bbt8VVzyqFl38H5h0FLAVIaSqFn3fNDmDfUgqV8CJiOJGu14pQNTq42QZG8CE5JEjXIKXVCQQ1oQmKZN%2Fa5xU%2FkgpKWBSapHbQPUtF1IGpT5pqhH7QgUVYZIcrZ4U5Sj1ttvgZo00vxN6KZ1ZO6UotZ7NnvYbwMhjLSBxza7qJ0AoelEwqyjVgdCaYAEMmrqykBJ4VRuZpH3DpACOIXB6wwGWQNaw4YT9dOblq21YJJiH0maP1GDxUigzMgdy9VhcTo%2B%2FG3ojqbLsGh1jRhisQp95Ma%2BWK4Gy1T0DLQlDPEv1X2Xr4VYWO8AAAAASUVORK5CYII%3D)
![Modrinth Downloads](https://img.shields.io/modrinth/dt/TZOteSf2?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB3aWR0aD0iNTEyIiBoZWlnaHQ9IjUxNCIgdmlld0JveD0iMCAwIDUxMiA1MTQiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI%2BCiAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik01MDMuMTYgMzIzLjU2QzUxNC41NSAyODEuNDcgNTE1LjMyIDIzNS45MSA1MDMuMiAxOTAuNzZDNDY2LjU3IDU0LjIyOTkgMzI2LjA0IC0yNi44MDAxIDE4OS4zMyA5Ljc3OTkxQzgzLjgxMDEgMzguMDE5OSAxMS4zODk5IDEyOC4wNyAwLjY4OTk0MSAyMzAuNDdINDMuOTlDNTQuMjkgMTQ3LjMzIDExMy43NCA3NC43Mjk4IDE5OS43NSA1MS43MDk4QzMwNi4wNSAyMy4yNTk4IDQxNS4xMyA4MC42Njk5IDQ1My4xNyAxODEuMzhMNDExLjAzIDE5Mi42NUMzOTEuNjQgMTQ1LjggMzUyLjU3IDExMS40NSAzMDYuMyA5Ni44MTk4TDI5OC41NiAxNDAuNjZDMzM1LjA5IDE1NC4xMyAzNjQuNzIgMTg0LjUgMzc1LjU2IDIyNC45MUMzOTEuMzYgMjgzLjggMzYxLjk0IDM0NC4xNCAzMDguNTYgMzY5LjE3TDMyMC4wOSA0MTIuMTZDMzkwLjI1IDM4My4yMSA0MzIuNCAzMTAuMyA0MjIuNDMgMjM1LjE0TDQ2NC40MSAyMjMuOTFDNDY4LjkxIDI1Mi42MiA0NjcuMzUgMjgxLjE2IDQ2MC41NSAzMDguMDdMNTAzLjE2IDMyMy41NloiIGZpbGw9IiMxYmQ5NmEiLz4KICA8cGF0aCBkPSJNMzIxLjk5IDUwNC4yMkMxODUuMjcgNTQwLjggNDQuNzUwMSA0NTkuNzcgOC4xMTAxMSAzMjMuMjRDMy44NDAxMSAzMDcuMzEgMS4xNyAyOTEuMzMgMCAyNzUuNDZINDMuMjdDNDQuMzYgMjg3LjM3IDQ2LjQ2OTkgMjk5LjM1IDQ5LjY3OTkgMzExLjI5QzUzLjAzOTkgMzIzLjggNTcuNDUgMzM1Ljc1IDYyLjc5IDM0Ny4wN0wxMDEuMzggMzIzLjkyQzk4LjEyOTkgMzE2LjQyIDk1LjM5IDMwOC42IDkzLjIxIDMwMC40N0M2OS4xNyAyMTAuODcgMTIyLjQxIDExOC43NyAyMTIuMTMgOTQuNzYwMUMyMjkuMTMgOTAuMjEwMSAyNDYuMjMgODguNDQwMSAyNjIuOTMgODkuMTUwMUwyNTUuMTkgMTMzQzI0NC43MyAxMzMuMDUgMjM0LjExIDEzNC40MiAyMjMuNTMgMTM3LjI1QzE1Ny4zMSAxNTQuOTggMTE4LjAxIDIyMi45NSAxMzUuNzUgMjg5LjA5QzEzNi44NSAyOTMuMTYgMTM4LjEzIDI5Ny4xMyAxMzkuNTkgMzAwLjk5TDE4OC45NCAyNzEuMzhMMTc0LjA3IDIzMS45NUwyMjAuNjcgMTg0LjA4TDI3OS41NyAxNzEuMzlMMjk2LjYyIDE5Mi4zOEwyNjkuNDcgMjE5Ljg4TDI0NS43OSAyMjcuMzNMMjI4Ljg3IDI0NC43MkwyMzcuMTYgMjY3Ljc5QzIzNy4xNiAyNjcuNzkgMjUzLjk1IDI4NS42MyAyNTMuOTggMjg1LjY0TDI3Ny43IDI3OS4zM0wyOTQuNTggMjYwLjc5TDMzMS40NCAyNDkuMTJMMzQyLjQyIDI3My44MkwzMDQuMzkgMzIwLjQ1TDI0MC42NiAzNDAuNjNMMjEyLjA4IDMwOC44MUwxNjIuMjYgMzM4LjdDMTg3LjggMzY3Ljc4IDIyNi4yIDM4My45MyAyNjYuMDEgMzgwLjU2TDI3Ny41NCA0MjMuNTVDMjE4LjEzIDQzMS40MSAxNjAuMSA0MDYuODIgMTI0LjA1IDM2MS42NEw4NS42Mzk5IDM4NC42OEMxMzYuMjUgNDUxLjE3IDIyMy44NCA0ODQuMTEgMzA5LjYxIDQ2MS4xNkMzNzEuMzUgNDQ0LjY0IDQxOS40IDQwMi41NiA0NDUuNDIgMzQ5LjM4TDQ4OC4wNiAzNjQuODhDNDU3LjE3IDQzMS4xNiAzOTguMjIgNDgzLjgyIDMyMS45OSA1MDQuMjJaIiBmaWxsPSIjMWJkOTZhIi8%2BCjwvc3ZnPg%3D%3D)
[![Proxy Stats](https://img.shields.io/bstats/servers/12530?logo=minecraft&label=Servers)](https://bstats.org/plugin/velocity/LimboAPI/12530)
[![Proxy Stats](https://img.shields.io/bstats/players/12530?logo=minecraft&label=Players)](https://bstats.org/plugin/velocity/LimboAPI/12530)

Library for sending players to virtual servers (called limbo) \
[Описание и обсуждение на русском языке (spigotmc.ru)](https://spigotmc.ru/resources/limboapi-limboauth-limbofilter-virtualnye-servera-dlja-velocity.715/) \
[Описание и обсуждение на русском языке (rubukkit.org)](http://rubukkit.org/threads/limboapi-limboauth-limbofilter-virtualnye-servera-dlja-velocity.177904/)

Test server: [``ely.su``](https://hotmc.ru/minecraft-server-203216)

## See also

- [LimboAuth](https://github.com/Elytrium/LimboAuth) - Auth System built in virtual server (Limbo). Uses BCrypt, has TOTP 2FA feature. Supports literally any database due to OrmLite.
- [LimboFilter](https://github.com/Elytrium/LimboFilter) - Most powerful bot filtering solution for Minecraft proxies. Built with LimboAPI.

## Features of LimboAPI

- Send to the Limbo server during login process
- Send to the Limbo server during play process
- Send maps, items to player's virtual inventory
- Display player's XP
- Send Title, Chat, ActionBar
- Load world from world files like .schematic
- and more...

## How to

- Include ``limboapi-api`` to your Maven/Gradle project as compile-only
- Subscribe to ``LoginLimboRegisterEvent`` to send players to the Limbo server during login process
- Use ``LimboFactory`` to send players to the Limbo server during play process

## How to include it

#### Setup your project via adding our maven repository to your pom.xml or build.gradle file.

- Maven:

```xml
    <repositories>
        <repository>
            <id>elytrium-repo</id>
            <url>https://maven.elytrium.net/repo/</url>
        </repository>
    </repositories>

    <dependencies>
        <dependency>
            <groupId>net.elytrium.limboapi</groupId>
            <artifactId>api</artifactId>
            <version>1.1.26</version>
            <scope>provided</scope>
        </dependency>
    </dependencies>
```

- Gradle:

```groovy
    repositories {
        maven {
            setName("elytrium-repo")
            setUrl("https://maven.elytrium.net/repo/")
        }
    }

    dependencies {
        compileOnly("net.elytrium.limboapi:api:1.1.26")
    }
```

## Used Open Source projects

- [ProtocolSupport](https://github.com/ProtocolSupport/ProtocolSupport) - for modern->legacy block mappings
- [ViaVersion](https://github.com/ViaVersion/ViaVersion) - for modern string->integer block mappings

## Demo

- [LimboAuth](https://github.com/Elytrium/LimboAuth) - The auth plugin, that uses LimboAPI as a dependency at the basic level.
- [LimboFilter](https://github.com/Elytrium/LimboFilter) - The antibot solution, that uses LimboAPI as a dependency, using almost all available API methods, like Low-level Minecraft packet control.

## Donation

Your donations are really appreciated. Donations wallets/links/cards:

- MasterCard Debit Card (Tinkoff Bank): ``5536 9140 0599 1975``
- Qiwi Wallet: ``PFORG`` or [this link](https://my.qiwi.com/form/Petr-YSpyiLt9c6)
- YooMoney Wallet: ``4100 1721 8467 044`` or [this link](https://yoomoney.ru/quickpay/shop-widget?writer=seller&targets=Donation&targets-hint=&default-sum=&button-text=11&payment-type-choice=on&mobile-payment-type-choice=on&hint=&successURL=&quickpay=shop&account=410017218467044)
- Monero (XMR): 86VQyCz68ApebfFgrzRFAuYLdvd3qG8iT9RHcru9moQkJR9W2Q89Gt3ecFQcFu6wncGwGJsMS9E8Bfr9brztBNbX7Q2rfYS



Update 1.1.28


LimboAPI local build update - detailed notes

1. plugin/build.gradle

What changed:
- Normal resource processing no longer depends on the heavy generateMappings task.
- Mapping regeneration now only runs when the Gradle property regenerateMappings is provided.

Why:
- The original build tried to generate Minecraft mappings during normal builds.
- That made the build look stuck around 66% and also caused cleanup errors on Windows.
- The project already needs checked-in/runtime resources for normal jar builds.

Result:
- Normal shadowJar builds are much faster.
- The plugin jar can be built without regenerating all Minecraft version data.

Relevant behavior:
- Normal build:
  .\gradlew.bat :plugin:shadowJar --no-daemon

- Full mapping regeneration, only if needed:
  .\gradlew.bat :plugin:shadowJar --no-daemon -PregenerateMappings


2. generate-runtime-mappings.ps1

What changed:
- Added a local PowerShell generator script.
- It generates runtime mapping JSON files from cached Minecraft 1.21 reports and existing legacy mapping files.

Generated files include:
- plugin/src/main/resources/mapping/blocks.json
- plugin/src/main/resources/mapping/blocks_mapping.json
- plugin/src/main/resources/mapping/blockstates.json
- plugin/src/main/resources/mapping/blockstates_mapping.json
- plugin/src/main/resources/mapping/defaultblockproperties.json
- plugin/src/main/resources/mapping/legacyblocks.json
- plugin/src/main/resources/mapping/items.json
- plugin/src/main/resources/mapping/items_mapping.json
- plugin/src/main/resources/mapping/blockentities_mapping.json
- plugin/src/main/resources/mapping/tags.json

Why:
- After skipping heavy generateMappings in Gradle, several runtime mapping files were missing from the jar.
- LimboAPI loads these files during startup.
- Missing files caused NullPointerException crashes in:
  SimpleItemComponentManager
  SimpleBlock
  SimpleTagManager

Result:
- Runtime mapping files are now generated and packaged into the plugin jar.
- Startup can pass the virtual world initialization stage.


3. plugin/src/main/resources/mapping/data_component_types.json

What changed:
- Added item component type id definitions.

Why:
- SimpleItemComponentManager requires this file during startup.
- Without it, LimboAPI crashed at:
  SimpleItemComponentManager.<clinit>

Result:
- Item component manager can load component IDs.


4. plugin/src/main/resources/mapping/data_component_types_mapping.json

What changed:
- Added item component type mappings for 1.21 and 26.1 fallback.

Why:
- Modern Minecraft item packets use data components.
- LimboAPI needs component IDs for SetSlotPacket and item component writing.

Result:
- 26.1/latest protocol can fall back to available component mappings instead of crashing.


5. plugin/src/main/java/net/elytrium/limboapi/server/item/SimpleItemComponentManager.java

What changed:
- Added fallback lookup for item component ID maps.
- If an exact ProtocolVersion is not found, it uses the nearest lower available mapping.
- If no lower mapping exists, it uses the earliest available mapping.

Why:
- Velocity protocol 26.1/latest may not have an exact generated mapping entry.
- Previously this caused unsupported-version or missing-id crashes.

Result:
- Item component IDs are more tolerant across nearby/new protocol versions.


6. plugin/src/main/resources/mapping/blocks.json

What changed:
- Added/generated modern block registry IDs.

Why:
- SimpleBlock needs local block IDs for modern block names.
- Missing this file caused startup NPE at:
  SimpleBlock.init

Result:
- Modern block names can resolve to local IDs.


7. plugin/src/main/resources/mapping/blocks_mapping.json

What changed:
- Added/generated block ID mappings for legacy/current versions.

Why:
- SimpleBlock uses this file to resolve block IDs across WorldVersion values.

Result:
- Blocks can resolve across supported Minecraft versions.


8. plugin/src/main/resources/mapping/blockstates.json

What changed:
- Added/generated modern blockstate IDs.

Why:
- SimpleBlock needs blockstate string -> protocol id mapping.

Result:
- Modern blockstates like minecraft:stone or minecraft:chain[axis=y,waterlogged=false] can resolve.


9. plugin/src/main/resources/mapping/blockstates_mapping.json

What changed:
- Added/generated blockstate mappings.
- Included a legacy baseline entry plus 1.21 and 26.1 entries.

Why:
- SimpleBlock loops across ProtocolVersion.SUPPORTED_VERSIONS and expects IDs to be parseable.
- Missing early entries could lead to null/string parse issues.

Result:
- Blockstate lookup is stable during startup.


10. plugin/src/main/resources/mapping/defaultblockproperties.json

What changed:
- Added/generated default block properties.

Why:
- SimpleBlock uses default properties when converting a plain block id into a specific blockstate.

Result:
- Blocks with properties can resolve their default state.


11. plugin/src/main/resources/mapping/legacyblocks.json

What changed:
- Fixed/generated correct format.
- Values are now numeric modern blockstate IDs, not names.

Before problem:
  "0": "minecraft:air"

Correct format:
  "0": "0"
  "1": "1"

Why:
- SimpleBlock expects legacy block id -> numeric modern blockstate id.
- Wrong string values caused:
  NumberFormatException: For input string: "minecraft:air"

Result:
- Legacy block IDs load correctly.


12. plugin/src/main/resources/mapping/items.json

What changed:
- Added/generated modern item registry IDs.

Why:
- SimpleItem needs this file during startup.

Result:
- Modern item IDs can resolve.


13. plugin/src/main/resources/mapping/items_mapping.json

What changed:
- Added/generated item version mappings.

Why:
- SimpleItem needs item IDs per WorldVersion.

Result:
- Items can resolve across supported versions.


14. plugin/src/main/resources/mapping/blockentities_mapping.json

What changed:
- Added/generated block entity mappings.

Why:
- SimpleBlockEntity requires this file during init.

Result:
- Block entity type IDs can resolve.


15. plugin/src/main/resources/mapping/tags.json

What changed:
- Added/generated flattened tags for:
  minecraft:block
  minecraft:item
  minecraft:fluid
- Added empty safe sections for:
  minecraft:entity_type
  minecraft:damage_type
  minecraft:banner_pattern

Why:
- SimpleTagManager requires /mapping/tags.json during startup.
- Missing file caused:
  SimpleTagManager.init NullPointerException

Result:
- Tags can be loaded and converted into UpdateTagsPacket.


16. plugin/src/main/java/net/elytrium/limboapi/server/world/SimpleBlock.java

What changed:
- fromModernID now safely returns AIR when a remapped/unknown block is not present in local block mappings.
- remapModernID now applies a remap only when the remap target exists in MODERN_BLOCK_STRING_MAP.

Why:
- modern_block_id_remap.json remaps:
  minecraft:chain -> minecraft:iron_chain
- The bundled registry has minecraft:chain, but not minecraft:iron_chain.
- This caused:
  IllegalStateException: failed to find local id for specific block: minecraft:iron_chain

Result:
- Unsupported/remapped block IDs no longer crash startup.
- minecraft:chain no longer becomes minecraft:iron_chain unless iron_chain exists in mappings.


17. plugin/src/main/java/net/elytrium/limboapi/server/LimboImpl.java

What changed:
- Fixed minecraft:zombie_nautilus_variant registry for Minecraft 1.21.11+.
- Added temperate and warm zombie nautilus variants with proper data shape.

Why:
- Issue #226 reported clients rejecting an invalid/empty zombie nautilus registry.

Result:
- 1.21.11+ registry sync includes valid zombie nautilus variant entries.


18. Runtime errors fixed from provided logs

Fixed:
- Current LimboAPI jar missing modern protocol support warning.
- Duplicate PlayerChatSessionPacket registration issue was avoided by using updated source mappings.
- SimpleItemComponentManager missing resource crash.
- SimpleBlock missing blocks.json crash.
- SimpleBlock legacyblocks NumberFormatException.
- SimpleTagManager missing tags.json crash.
- SimpleTagManager/SimpleBlock crash from minecraft:chain remapping to minecraft:iron_chain.


19. Notes

- LimboAuth errors in the pasted logs are downstream because LimboAPI failed to load first.
- After replacing LimboAPI with the latest jar, retest Velocity startup.
- If LimboAPI loads successfully but LimboAuth still errors, that will be a separate LimboAuth issue.


20. File to use

Use this jar:
plugin/build/libs/limboapi-1.1.27-SNAPSHOT.jar

Replace the old LimboAPI jar in Velocity plugins with this file.
