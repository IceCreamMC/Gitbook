# Configuration

```yaml
# This is the main configuration file for IceCream.
# If you need help with the configuration or have any questions related to IceCream,
# join us in our Discord server.
#
# Discord: https://discord.gg/zhvU2PRfFg 
# Docs: COMING SOON 
# New builds: https://github.com/IceCreamMC/IceCream/releases/latest

verbose: false
settings:
  do-not-process-chat-commands: true
  villagers:
    simpler-behavior: false
    hide-at-night: false
collisions:
  players: true
  animals: true
  ambient: true
  monsters: true
  villagers: true
  pillagers: true
  iron-golems: true
  misc: true
  items: true
  water-ambient: true
  water-creatures: true
  underground-water-creatures: true
  axolotls: true
world-settings:
  default:
    blocks:
      farmland:
        water-seek-range: 4
        gets-moist-from-water-cauldron: false
config-version: 3
```

## verbose

Sets whether the server should dump all configuration values to the server log on startup (this might not be functional right now)



## do-not-process-chat-commands

Commands will not be proceeded while the player is joining the server



### simpler-behavior

Make villagers simpler!



### hide-at-night

Whether villagers hide at night or not.



### collisions:

Toggle collisions



### water-seek-range

Change how many blocks a water source can make farmland moist. For example, if the value is 8, your farm can be 8x8



### gets-moist-from-water-cauldron

Whether you want farmland to get moist from water cauldrons or not



### config-version

**Do not change this!** This is the version for the configuration file.
