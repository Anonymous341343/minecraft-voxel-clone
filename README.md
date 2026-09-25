# VoxelCraft

A small Minecraft-inspired voxel survival prototype built with Three.js.

## Features

- Procedural voxel terrain
- Block breaking and placement
- Simple hotbar inventory
- Textured blocks generated at runtime
- Mobs with simple movement
- Chat and slash commands

## Run locally

Open `index.html` in a browser, or serve the folder with a local static server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Controls

- WASD = move
- Space = jump
- Left click = break block
- Right click = place block
- 1-9 = select block
- T = open chat
- /help = command list

## Commands

- `/help`
- `/tp x y z` - teleport to coordinates
- `/time set <value>` - set time of day
- `/weather day|night` - change lighting
- `/give grass|dirt|stone|wood|leaves|sand|cobblestone|planks|ore` - get item
- `/summon zombie|sheep` - spawn a mob
- `/heal` - restore health and hunger
- `/gamemode creative|survival` - change game mode

## Mob Behavior

- **Zombies** - Green mobs that wander aimlessly
- **Sheep** - White mobs that wander slowly

## Block Types

- Grass, Dirt, Stone, Cobblestone
- Wood, Leaves, Planks
- Sand
- Ore

## To-Do

- Proper crafting system
- Tools with different break speeds
- Damage and health system
- More natural terrain generation
- Water and lava
- Biome variations
