# Camman18 Minecart Boss

## What it does

- Spawns a giant boss when a player rides any minecart
- Plays a loud scream and shows the meme line in chat
- Uses a close-range hit and a ranged sonic-boom-style attack
- Makes the boss take damage only from birch wood items in the player's hand

## Files to open

Open the folder in IntelliJ IDEA or another Java IDE as a Gradle project.

## Run

Use the Gradle task:

```bash
runClient
```

## Notes

- This project targets Minecraft 1.19.4, Java 17, and Fabric.
- The boss is a vanilla `GiantEntity`, so there is no custom model needed yet.
- If you want a custom skin, boss bar, or real voice line later, those can be added on top of this base.
