# race-mode
The definitive race game mode for Halo Infinite

[Bookmark Here!](https://www.halowaypoint.com/en-gb/halo-infinite/ugc/modes/6ff26100-5290-4499-b51e-34e2a93de059)

## Table of Contents
- [How to Play](#how-to-play)
  - [Settings](#settings)
- [Map Setup](#map-setup)
  - [Settings Objects](#settings-objects)
  - [Initial Spawns](#initial-spawns)
  - [Checkpoints](#checkpoints)
  - [Debugging](#debugging)
  - [Metadata](#metadata)



![Race Mode Thumbnail](https://blobs-infiniteugc.svc.halowaypoint.com/ugcstorage/ugcgamevariant/6ff26100-5290-4499-b51e-34e2a93de059/0d811590-42de-46a9-9650-1d222cc511fa/images/screenshot1.jpg)

## How to Play
Bookmark and play the race game mode [here.](https://www.halowaypoint.com/en-gb/halo-infinite/ugc/modes/6ff26100-5290-4499-b51e-34e2a93de059)

Check out compatible maps [here.](https://www.halowaypoint.com/en-gb/halo-infinite/ugc/browse?assetKind=Map&page=1&tags=arace)

### Settings
Play the mode exactly how you want with these customs settings. For the minigame object settings, include = true and exclude = false.


| Setting | Location in Menu | Default Value |
| ------- | ---------------- | ------------- |
| Number of Laps | Match -> Score to Win | 3 |
| Vehicle for Race | Minigame -> Spawn in Vehicle | Mongoose |
| Force Stay in Vehicle | Minigame -> Use 'Minigame Object 2' | Include |
| Mini Vehicles | Minigame -> Use 'Minigame Object 3' | Exclude |
| Allow all players to finish | Minigame -> Use 'Minigame Object 4' | Exclude |
| Show Checkpoints | Minigame -> Use 'Minigame Object 5' | Exclude |

Check out Forks of the mode with preset settings [here.](https://www.halowaypoint.com/en-gb/halo-infinite/ugc/browse?assetKind=UgcGameVariant&page=1&tags=arace)

## Map Setup
### Settings Objects
Add this prefab to your race map to ensure the configurable minigame object settings work. Without it all the settings will always be set to exclude no matter what the player has set. 
https://www.halowaypoint.com/en-gb/halo-infinite/ugc/prefabs/2dabd8d5-d7f7-44cb-8795-d2a175d10228
### Initial Spawns
Place initial spawns at the start of the track for players to spawn at. Set them far enough apart from eachother so the vehicles aren't touching when theh spawn in. If you are setting this mode up on a map with existing initial spawns you will have to set them to minigame exclude however this may conflict with other modes.
### Checkpoints
Each checkpoint needs at least 1 spawn point attached to it via prefabbing. Any spawn point not attached to checkpoint will be disabled. 

Checkpoints are set in the order they are placed on the map however unprefabbing and then duplicating can mess with the order. So, the best way to set the map up is to add all the checkpoints to the map first, and then going through to resize and modify spawns. 
https://www.halowaypoint.com/en-gb/halo-infinite/ugc/prefabs/39693a0a-eae0-4e28-be4a-f9dad8fe0149
### Debugging
### Metadata
To make it easier to identify maps that are compatible with the mode, I recommend adding the tag `ARace` to your map.

Another thing you can do to help make your map identifiable at a glance is to overlay the following image on your map thumbnail.
![Thumbnail Overlay](https://cdn.discordapp.com/attachments/1262918449009660025/1263308979820560445/RaceBoarder.png?ex=669a6c6b&is=66991aeb&hm=203ea39fde9932d6ba31f18bc15673157383b9209745d15587ab4e2a45749cfd&)
