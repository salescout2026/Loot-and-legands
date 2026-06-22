# QuestForge5E: Loot & Legends

This repo now contains a complete playable QuestForge5E web/PWA build centered on **The Shattered Coast** adventure pack.

## What is included

- Character creation
- Medieval parchment fantasy UI
- Quest board with handcrafted quests
- Completed quests disappear permanently from the board
- Branching story flags and consequences
- Scrollable visual world map with active route progress
- Simple 5E-inspired d20 checks and combat
- Shipyard screen with visible ship and upgrades
- Inventory, gold, reputation, HP, XP, and local save/load
- Major story quest: **The Bell Beneath the Sea**
- Multiple endings based on player choices

## Handcrafted quests

1. **Rats in the Cellar** - a starter cellar quest that reveals old smugglers' tunnels.
2. **The Lantern on Widow's Rock** - a lighthouse mystery with a frightened smuggler and the Blue Flame Lantern.
3. **The Blackroot Cure** - a marsh medicine quest with a goblin moral choice.
4. **The Missing Cart** - a road investigation that reveals the bone-masked cult.
5. **The Bell Beneath the Sea** - the main story dungeon and boss quest against Marrow-Speaker Vael.

## Run locally

Open `index.html` in a browser, or run:

```bash
npm run serve
```

Then open the local address shown by Python.

## Android APK

The included GitHub Actions workflow builds a debug APK using Capacitor. After pushing to `main`, open the **Actions** tab, run **Build Android Debug APK**, and download the `QuestForge5E-debug-apk` artifact.

