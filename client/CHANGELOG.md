## [4.0.0] - 2025-03-10

Major update yippee! Finally got myself to debug this sh*t because it's getting worse. Thanks to [Imperium](https://thunderstore.io/c/lethal-company/p/giosuel/Imperium/) and [Lethal Sponge](https://thunderstore.io/c/lethal-company/p/Scoops/LethalSponge/) I was able to identify all heavy stuff.

I've also added a huge load of fix/performance mods, as well as config changes. Moved host-only mods and performance mods to separate manifests.

## Added

- [Country Road Creature](https://thunderstore.io/c/lethal-company/p/Wexop/CountryRoadCreature/)
- [Football](https://thunderstore.io/c/lethal-company/p/Kittenji/Football/)
- [Oiia Cat](https://thunderstore.io/c/lethal-company/p/Luxciano32/OiiaCat/)
- [SCP-4666](https://thunderstore.io/c/lethal-company/p/ProjectSCP/SCP4666/)
- [Locker](https://thunderstore.io/c/lethal-company/p/zealsprince/Locker/)
- [Fashion Company](https://thunderstore.io/c/lethal-company/p/Dwarggo/Fashion_Company/)
- [Lethal Elements Beta](https://thunderstore.io/c/lethal-company/p/v0xx/LethalElementsBeta/)
- [Problematic Pilotry](https://thunderstore.io/c/lethal-company/p/windblownleaves/ProblematicPilotry/)
- [Synthesis](https://thunderstore.io/c/lethal-company/p/luakite/Synthesis_Moon/)
- [Vacuity](https://thunderstore.io/c/lethal-company/p/luakite/Vacuity_Moon/)
- [Additional Networking](https://thunderstore.io/c/lethal-company/p/mattymatty/AdditionalNetworking/)
- [Better EXP](https://thunderstore.io/c/lethal-company/p/Swaggies/BetterEXP/)
- [Buttery Fixes](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/ButteryFixes/)
- [Less Logs](https://thunderstore.io/c/lethal-company/p/falcodxb/LessLogs/)
- [Lethal Sponge](https://thunderstore.io/c/lethal-company/p/Scoops/LethalSponge/)
- [Pathfinding Lag Fix Beta](https://thunderstore.io/c/lethal-company/p/Zaggy1024/PathfindingLagFix_Beta/)
- [Reverb Trigger Fix](https://thunderstore.io/c/lethal-company/p/JacobG5/ReverbTriggerFix/)
- [Uni Task](https://thunderstore.io/c/lethal-company/p/Bobbie/UniTask/)
- [Hazards Outside](https://thunderstore.io/c/lethal-company/p/snake_tech/HazardsOutside/) (to [host pack](https://thunderstore.io/c/lethal-company/p/PAXANDDOS/AurelionPack_Host))
- [Lobby Control](https://thunderstore.io/c/lethal-company/p/mattymatty/LobbyControl/) (to [host pack](https://thunderstore.io/c/lethal-company/p/PAXANDDOS/AurelionPack_Host))
- [Lost Enemy Fix](https://thunderstore.io/c/lethal-company/p/JacobG5/LostEnemyFix/) (to [host pack](https://thunderstore.io/c/lethal-company/p/PAXANDDOS/AurelionPack_Host))
- [Majority Vote](https://thunderstore.io/c/lethal-company/p/MrHydralisk/MajorityVote/) (to [host pack](https://thunderstore.io/c/lethal-company/p/PAXANDDOS/AurelionPack_Host))
- [Lethal Progression (Patch Fix)](https://thunderstore.io/c/lethal-company/p/Chibranche/LethalProgression_PatchFix_keepProgress/) replaced Lethal Progression

## Changed

- **Huntdown**:
  - disabled Bug Mafia mission
  - disabled Thumper mission
  - enabled Good Boy mission
  - enabled Infestation mission
  - enabled Last Months Interns mission
  - enabled Last Months Interns mission
- **Less Logs**:
  - disabled "warning" log level for Scarlet Mansion, Little Company, Biodiversity, Weather Registry, Buttery Fixes, Lethal Level Loader, Mattys Fixes, Additional Networking, Loadstone, Dungeon Generation Plus, Remnants, Reserved Item Slot Core, Solids Library, Too Many Emotes Scrap, MoreHead, Terminal Formatter, Lethal Fixes
  - disabled "error" log level for Wesleys Interior Shenanigans
- **Async Loggers**: 
  - reduced sqlite max size (100MB -> 50MB)
  - changed Unity log level (Warning -> Error)
- **Problematic Pilotry**: 
  - reduced landing ship probability (100% -> 80%)
  - reduced dropship probability (100% -> 70%)
- **MajorityVote**: 
  - reduced vote percentage (0.5 -> 0.4)
  - increased minumum votes needed (1 -> 2)
- **Lethal Sponge**: 
  - disabled fixFoliageLOD 
  - enabled minimal logging
  - increased fog budget (0.15 -> 0.16)
- **Lethal Fixes**: 
- **Ghost Codes**: disabled extensive logging
- **JLL**: reduced logging (User -> ImportantOnly)
- **Buyable Shotgun Plus**: reduced shotgun price (666 -> 300)
- **Weather Registry**: disabled debug logging
- **Ship Windows**: enabled window shutter

## Updated

- [Surfaced](https://thunderstore.io/c/lethal-company/p/SurfacedTeam/Surfaced/) `1.5.2` -> `1.5.3`
- [Chillax Scrap](https://thunderstore.io/c/lethal-company/p/Zigzag/ChillaxScraps/) `1.5.7` -> `1.5.8`
- [Premium Scraps](https://thunderstore.io/c/lethal-company/p/Zigzag/PremiumScraps/) `2.3.2` -> `2.3.3`
- [Lethal Performance](https://thunderstore.io/c/lethal-company/p/DiFFoZ/LethalPerformance/) `0.5.0` -> `0.6.0`
- [loaforcs Sound API](https://thunderstore.io/c/lethal-company/p/loaforc/loaforcsSoundAPI/) `2.0.4` -> `2.0.5`
- [Huntdown](https://thunderstore.io/c/lethal-company/p/doggosuki/Huntdown/) `1.6.3` -> `1.6.4`
- [Generic Interiors](https://thunderstore.io/c/lethal-company/p/Generic_GMD/Generic_Interiors/) `1.6.3` -> `1.6.4`
- [Emergency Dice](https://thunderstore.io/c/lethal-company/p/slayer6409/Emergency_Dice_Updated/) `1.9.7` -> `1.9.11`
- [AsyncLoggers](https://thunderstore.io/c/lethal-company/p/mattymatty/AsyncLoggers/) `2.1.3` -> `2.1.4`
- [JLL](https://thunderstore.io/c/lethal-company/p/JacobG5/JLL/) `1.9.2` -> `1.9.3`
- [General Improvements](https://thunderstore.io/c/lethal-company/p/ShaosilGaming/GeneralImprovements/) `1.4.8` -> `1.4.9`
- [DetourContext Dispose Fix](https://thunderstore.io/c/lethal-company/p/Hamunii/DetourContext_Dispose_Fix/) `1.0.3` -> `1.0.4`
- [AutoHook Gen Patcher](https://thunderstore.io/c/lethal-company/p/Hamunii/AutoHookGenPatcher/) `1.0.4` -> `1.0.6`
- [Mirage](https://thunderstore.io/c/lethal-company/p/qwbarch/Mirage/) `1.18.2` -> `1.19.0`
- [Reserved Item Slot Core](https://thunderstore.io/c/lethal-company/p/FlipMods/ReservedItemSlotCore/) `2.0.44` -> `2.0.47`
- [Premium Scraps](https://thunderstore.io/c/lethal-company/p/Zigzag/PremiumScraps/) `2.3.3` -> `2.3.4`

## Removed

- [Dead And Bored](https://thunderstore.io/c/lethal-company/p/Quixler/DeadAndBored/)
- [Frosty Suits](https://thunderstore.io/c/lethal-company/p/happyfrosty/FrostySuits/)
- [Men Stalker](https://thunderstore.io/c/lethal-company/p/YaBoiDucki/men_stalker/)
- [Lethal Rich Presence](https://thunderstore.io/c/lethal-company/p/mrov/LethalRichPresenceExperimental/)
- [Remove Interior Fog](https://thunderstore.io/c/lethal-company/p/Zehs/RemoveInteriorFog/)
- [SCP 106](https://thunderstore.io/c/lethal-company/p/Dackie/SCP106/)
- [Telepathic Object](https://thunderstore.io/c/lethal-company/p/MrUnrealTeam/TelepathicObject/)
- [LethalProgression](https://thunderstore.io/c/lethal-company/p/Stoneman/LethalProgression/)
- [Huntdown](https://thunderstore.io/c/lethal-company/p/doggosuki/Huntdown/) (moved to the [host pack](https://thunderstore.io/c/lethal-company/p/PAXANDDOS/AurelionPack_Host))
- [Faster Item Dropship](https://thunderstore.io/c/lethal-company/p/FlipMods/FasterItemDropship/) (moved to the [host pack](https://thunderstore.io/c/lethal-company/p/PAXANDDOS/AurelionPack_Host))
- [FairAI](https://thunderstore.io/c/lethal-company/p/TheFluff/FairAI/) (moved to the [host pack](https://thunderstore.io/c/lethal-company/p/PAXANDDOS/AurelionPack_Host))
- [Malfunctions](https://thunderstore.io/c/lethal-company/p/zealsprince/Malfunctions/) (moved to the [host pack](https://thunderstore.io/c/lethal-company/p/PAXANDDOS/AurelionPack_Host))
- [Lunxaras Menu Theme](https://thunderstore.io/c/lethal-company/p/Lunxara/Lunxaras_Menu_Theme/) (provided custom one within modpack)
- [Dark Mist](https://thunderstore.io/c/lethal-company/p/Frack9/DarkMist/) (main reason for host (=>clients) lags)
- [Symbiosis](https://thunderstore.io/c/lethal-company/p/NiceHairs/Symbiosis/) (huge log clutter in certain conditions)
- [Diversity](https://thunderstore.io/c/lethal-company/p/IntegrityChaos/Diversity/) (oh my god it was the main reason of low fps and full darkness)
- [Terbium](https://thunderstore.io/c/lethal-company/p/loaforc/Terbium/) (functions presumably coded in LethalPerformance and/or Loadstone)

## [3.2.1] - 2025-03-01

### Added

- [Suit Saver](https://thunderstore.io/c/lethal-company/p/Hexnet111/SuitSaver/)

### Updated

- [Emergency Dice](https://thunderstore.io/c/lethal-company/p/slayer6409/Emergency_Dice_Updated/) `1.9.7` -> `1.9.8`
- [Huntdown](https://thunderstore.io/c/lethal-company/p/doggosuki/Huntdown/) `1.6.2` -> `1.6.3`

## [3.2.0] - 2025-02-28

Due to performance reasons we're removing models, quite sad but I'll see if it helps the situation (my friends literally play in 20fps). Adding cosmetics instead.

### Added

- [Dead And Bored](https://thunderstore.io/c/lethal-company/p/Quixler/DeadAndBored/)
- [Ghost Codes](https://thunderstore.io/c/lethal-company/p/darmuh/ghostCodes/)
- [Huntdown](https://thunderstore.io/c/lethal-company/p/doggosuki/Huntdown/)
- [Reserved Flashlight Slot](https://thunderstore.io/c/lethal-company/p/FlipMods/ReservedFlashlightSlot/)
- [Sell From Terminal](https://thunderstore.io/c/lethal-company/p/stormytuna/SellFromTerminal/)
- [Devil May Company](https://thunderstore.io/c/lethal-company/p/loserlilith/DevilMayCompany/)
- [Erics Scrap Helmet](https://thunderstore.io/c/lethal-company/p/EricsTeam/EricsScrap_Helmet/)
- [Frosty Suits](https://thunderstore.io/c/lethal-company/p/happyfrosty/FrostySuits/)
- [Fortnite Furry Girl Cosmetics](https://thunderstore.io/c/lethal-company/p/RazzyRazRaz/Fortnite_Furry_Girl_Cosmetics/)
- [Goon Suits](https://thunderstore.io/c/lethal-company/p/ironbean/goonsuits/)
- [More Head](https://thunderstore.io/c/lethal-company/p/Mhz/MoreHead/)
- [Nikkis Cosmetic Kingdom](https://thunderstore.io/c/lethal-company/p/Nikki/NikkisCosmeticKingdom/)
- [Simple Hats](https://thunderstore.io/c/lethal-company/p/fonnymunkey/SimpleHats/)
- [Ukrainian Core Suits](https://thunderstore.io/c/lethal-company/p/DarkMorosh/Ukrainian_Core_Suits/)

### Changed

- **Too Many Emotes** (not enough):
  - increased number of emotes in store rotation (6 -> 8)
  - increased starting emote credits (100 -> 300)
  - increased credits multiplier (0.333 -> 0.4)
  - increased likelyhood of epic emote (0.135 -> 0.18)
  - increased likelyhood of legendary emote (0.015 -> 0.09)
  - reduced likelyhood of common emote (0.5 -> 0.45)
  - reduced epic emote price (200 -> 150)
  - reduced legendary emote price (300 -> 200)
- **Telepathic Object**:
  - increased spawn chance (50 -> 150) (wtf slider range is 0 through 99999)
  - reduced speed in chase  (6 -> 4.5)
  - reduced distance to melee (7.5 -> 6)
- **Suits Terminal**:
  - disabled banner hints
  - set change page as default menu
- **Lethal Progression**:
  - increased health regen multiplier (0.05 -> 0.09)
  - increased stamina multiplier (2 -> 3.2)
- **Huntdown**:
  - disabled Bracken mission
  - disabled Good Boy mission
  - disabled Infestation mission
  - disabled Last Months Interns mission
- **Ship Windows**:
  - unlocked door windows by default
  - disabled Wesley shutter voice
  - disable shutter scan node
  - disabled window shutter
- **More Suits**: reverted to defaults
- **Too Many Suits**: reverted to defaults

### Updated

- [Lategame Upgrades](https://thunderstore.io/c/lethal-company/p/malco/Lategame_Upgrades/) `3.12.1` -> `3.12.2`
- [Emergency Dice](https://thunderstore.io/c/lethal-company/p/slayer6409/Emergency_Dice_Updated/) `1.9.3` -> `1.9.7`
- [Men Stalker](https://thunderstore.io/c/lethal-company/p/YaBoiDucki/men_stalker/) `2.5.5` -> `2.5.7`
- [Wesleys Interiors](https://thunderstore.io/c/lethal-company/p/Magic_Wesley/WesleysInteriors/) `2.0.11` -> `2.1.0`
- [JLL](https://thunderstore.io/c/lethal-company/p/JacobG5/JLL/) `1.9.1` -> `1.9.2`
- [Atlantica](https://thunderstore.io/c/lethal-company/p/Magic_Wesley/Atlantica/) `4.0.1` -> `4.1.2`
- [MrovLib](https://thunderstore.io/c/lethal-company/p/mrov/MrovLib/) `0.2.22` -> `0.2.23`

### Removed

- [Escanor](https://thunderstore.io/c/lethal-company/p/Drunger/Escanor_Model/)
- [Gabriel](https://thunderstore.io/c/lethal-company/p/doppelwrangler/Gabriel_Suit/)
- [Ghostface](https://thunderstore.io/c/lethal-company/p/BruhMMods/LethalGhostface/)
- [Hunk](https://thunderstore.io/c/lethal-company/p/Yakutare/HunkModel/)
- [Loona](https://thunderstore.io/c/lethal-company/p/Unga_bunga/loona/)
- [Mirasuits](https://thunderstore.io/c/lethal-company/p/Mirayah/Mirasuits/)
- [Rocket Racoon](https://thunderstore.io/c/lethal-company/p/YaBoyCamo/Rocket_Raccoon_Playermodel/)
- [Zenless Zone Zero](https://thunderstore.io/c/lethal-company/p/inki/ZenlessZoneZeroSuits/)
- [Herobrine](https://thunderstore.io/c/lethal-company/p/Kittenji/Herobrine/)
- [Gojo Scrap](https://thunderstore.io/c/lethal-company/p/lvnqa/GojoScrap/)
- [Office](https://thunderstore.io/c/lethal-company/p/Piggy/LC_Office/)
- [Cruiser Phonk Edition](https://thunderstore.io/c/lethal-company/p/rkadery/CruiserPhonkEdition/)
- [Lethal Presents](https://thunderstore.io/c/lethal-company/p/Azim/LethalPresents/) (doesn't work?)
- [Meme Soundboard](https://thunderstore.io/c/lethal-company/p/Flof/MemeSoundboard/) (bugs out)
- [Suit Saver](https://thunderstore.io/c/lethal-company/p/Hexnet111/SuitSaver/) (exists in General Improvements)

## [3.1.3] - 2025-02-24

### Added

- [Generic Interiors](https://thunderstore.io/c/lethal-company/p/Generic_GMD/Generic_Interiors/)
- [Generic Moons](https://thunderstore.io/c/lethal-company/p/Generic_GMD/Generic_Moons/)
- [Wesleys Interiors](https://thunderstore.io/c/lethal-company/p/Magic_Wesley/WesleysInteriors/)
- [Telepathic Object](https://thunderstore.io/c/lethal-company/p/MrUnrealTeam/TelepathicObject/)

### Updated

- [MrovLib](https://thunderstore.io/c/lethal-company/p/mrov/MrovLib/) `0.2.21` -> `0.2.22`
- [Emergency Dice](https://thunderstore.io/c/lethal-company/p/slayer6409/Emergency_Dice_Updated/) `1.9.1` -> `1.9.3`
- [Premium Scraps](https://thunderstore.io/c/lethal-company/p/Zigzag/PremiumScraps/) `2.3.1` -> `2.3.2`
- [Immersive Scrap](https://thunderstore.io/c/lethal-company/p/XuXiaolan/ImmersiveScrap/) `1.4.1` -> `1.4.2`
- [Too Many Emotes](https://thunderstore.io/c/lethal-company/p/FlipMods/TooManyEmotes/) `2.2.14` -> `2.3.1`

### Removed

- [Groan Tube](https://thunderstore.io/c/lethal-company/p/Kittenji/Groan_Tube_Scrap/)
- [Peepers](https://thunderstore.io/c/lethal-company/p/x753/Peepers/)
- [Karma For Being Annoying](https://thunderstore.io/c/lethal-company/p/dontless/KarmaForBeingAnnoying_UPDATED/)
- [Locker](https://thunderstore.io/c/lethal-company/p/zealsprince/Locker/)
- [Starlancer Warehouse](https://thunderstore.io/c/lethal-company/p/AudioKnight/StarlancerWarehouse/)

## [3.1.2] - 2025-02-23

### Added

- [Lunxaras Menu Theme](https://thunderstore.io/c/lethal-company/p/Lunxara/Lunxaras_Menu_Theme/)
- [Terminal Formatter](https://thunderstore.io/c/lethal-company/p/mrov/TerminalFormatter/)
- [Lethal Rich Presence](https://thunderstore.io/c/lethal-company/p/mrov/LethalRichPresenceExperimental/)
- [Celestial Tint](https://thunderstore.io/c/lethal-company/p/sfDesat/Celestial_Tint/)
- [Faster Item Dropship](https://thunderstore.io/c/lethal-company/p/FlipMods/FasterItemDropship/)
- [Emergency Dice](https://thunderstore.io/c/lethal-company/p/slayer6409/Emergency_Dice_Updated/)
- [Whiteboard](https://thunderstore.io/c/lethal-company/p/Zehs/Whiteboard/)
- [Remove Interior Fog](https://thunderstore.io/c/lethal-company/p/Zehs/RemoveInteriorFog/) (yet its still extremely dark for some reason)
- [Buyable Shotgun Plus](https://thunderstore.io/c/lethal-company/p/Entity378/BuyableShotgunPlus/) replaced BuyableShotgun and BuyableShotgunShells

### Changed

- **Whiteboard**: reduced price to 50
- **Faster Item Dropship**: reduced delivery time to 5

### Updated

- [More Suits](https://thunderstore.io/c/lethal-company/p/x753/More_Suits/) `1.4.5` -> `1.5.1`
- [Reserved Item Slot Core](https://thunderstore.io/c/lethal-company/p/FlipMods/ReservedItemSlotCore/) `2.0.43` -> `2.0.44`
- [Mask Fixes](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/MaskFixes/) `1.2.1` -> `1.2.2`

### Removed

- [Buyable Shotgun](https://thunderstore.io/c/lethal-company/p/MegaPiggy/BuyableShotgun/)
- [Buyable Shotgun Shells](https://thunderstore.io/c/lethal-company/p/MegaPiggy/BuyableShotgunShells/)

## [3.1.1] - 2025-02-22

### Changed

- **Elads HUD**: slightly decreased scale
- **General Improvements**: added danger level and total deaths to the monitors
- **Lethal Fixes**: removed voice activity icon, removed prop shadows

### Updated

- [ChillaxScraps](https://thunderstore.io/c/lethal-company/p/Zigzag/ChillaxScraps/) `1.5.6` -> `1.5.7`

## [3.1.0] - 2025-02-22

#### Modpack is now public!

### Added

- [Terbium](https://thunderstore.io/c/lethal-company/p/loaforc/Terbium/)
- [Lethal Resonance](https://thunderstore.io/c/lethal-company/p/LethalResonance/LETHALRESONANCE/) (which is now fixed)
- [Elads HUD](https://thunderstore.io/c/lethal-company/p/EladNLG/EladsHUD/)
- [Peepers](https://thunderstore.io/c/lethal-company/p/x753/Peepers/)
- [Locker](https://thunderstore.io/c/lethal-company/p/zealsprince/Locker/)
- [Surfaced](https://thunderstore.io/c/lethal-company/p/SurfacedTeam/Surfaced/)
- [Starlancer Moons](https://thunderstore.io/c/lethal-company/p/AudioKnight/StarlancerMoons/)
- [Starlancer Warehouse](https://thunderstore.io/c/lethal-company/p/AudioKnight/StarlancerWarehouse/)
- [Starlancer Enemy Escape](https://thunderstore.io/c/lethal-company/p/AudioKnight/StarlancerEnemyEscape/) replaced LethalEscape
- [Karma For Being Annoying UPDATED](https://thunderstore.io/c/lethal-company/p/dontless/KarmaForBeingAnnoying_UPDATED/) replaced KarmaForBeingAnnoying
- [Reserved Walkie Slot](https://thunderstore.io/c/lethal-company/p/FlipMods/ReservedWalkieSlot/) replaced WalkieUse
- [Minecraft Scraps](https://thunderstore.io/c/lethal-company/p/4902/Minecraft_Scraps/) replaced MinecraftScaps (deprecated dependency)

### Changed

- **BepInEx config**: disabled console for potential performance improvement. For debugging use %AppData%\r2modmanPlus-local\LethalCompany\profiles\{profile}\BepInEx\LogOutput.log
- **GeneralImprovements config**
- **Diversity config**: disabled cutscene, posters, and speaker
- **ReservedItemSlotCore config**: hid empty slots

### Updated

- [Mirasuits](https://thunderstore.io/c/lethal-company/p/Mirayah/Mirasuits/) `1.3.1` -> `1.4.1`
- [Mirage](https://thunderstore.io/c/lethal-company/p/qwbarch/Mirage/) `1.18.1` -> `1.18.2`
- [General Improvements](https://thunderstore.io/c/lethal-company/p/ShaosilGaming/GeneralImprovements/) `1.4.7` -> `1.4.8`
- [LethalCompanyInputUtils](https://thunderstore.io/c/lethal-company/p/Rune580/LethalCompany_InputUtils/) `0.7.7` -> `0.7.10`
- [Lethal Level Loader](https://thunderstore.io/c/lethal-company/p/IAmBatby/LethalLevelLoader/) `1.4.10` -> `1.3.11`

### Removed

- [Lethal Escape](https://thunderstore.io/c/lethal-company/p/xCeezy/LethalEscape/)
- [Karma For Being Annoying](https://thunderstore.io/c/lethal-company/p/CTMods/KarmaForBeingAnnoying/)
- [Minecraft Scraps](https://thunderstore.io/c/lethal-company/p/rainbow137/MinecraftScraps/)
- [Walkie Use](https://thunderstore.io/c/lethal-company/p/Renegades/WalkieUse/)
- Several other mods (replaced by General Improvements)

## [3.0.0] - 2025-02-14

Repackaged with new mods.
