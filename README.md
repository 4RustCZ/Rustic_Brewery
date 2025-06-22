
# 🍻 Rustic_Brewery — Minecraft Plugin

A custom Paper plugin for Minecraft that introduces brewing, alcohol discovery, and immersive drunkenness — all without requiring mods.

---

## ✅ Features

### 📘 Player Recipe Book
- Craftable book showing **only the player’s unlocked recipes**
- Recipes unlocked via crafting progression or scroll discovery
- Book always reflects the viewer’s progress (not transferable)

### 🍷 Alcohol Crafting System
- Multiple brewing stages:
  - 🏺 Vase (Mead)
  - 🪵 Barrel (Wine)
  - 🍺 Tank (Beer)
  - 🔥 Distillery (Spirits)
- Brewing requires ingredients, containers, and time
- Later stages use multiblock or custom blocks

### 📜 Unlocking & Progression
- **Historical path**: Start with primitive brewing and progress to distillation
- **Exploration path**: Discover scrolls in generated structures that unlock heavenly brews

### 🍾 Custom Alcohol Items
- Unique names, effects, and appearances
- “Heavenly” drinks grant potion buffs (e.g., Haste II for 5 minutes)

### 🤢 Drunkenness Effects
- Drinking alcohol increases a **drunkenness level**
- Drunken players:
  - Speak with **slurred text**
  - May **vomit** (particles, sounds, drop items)
  - Experience effects: Nausea, blindness, slowness
  - Can **pass out** if over-intoxicated

### 🧠 Persistent Player Memory
- Each player’s unlocked recipes are stored individually
- Unlock data persists across sessions

### 🎨 Optional Resource Pack
- Custom models for brewing equipment (vases, barrels, tanks, scrolls)
- Unique alcohol bottles with icons
- Visual stages of fermentation/distillation

---

## 🛠 Development Roadmap

### 📦 Core Setup
- [x] Plugin skeleton (`plugin.yml`, base classes)
- [ ] Player unlock tracking system
- [ ] Alcohol item registry (names, effects, lore)

### 🛠 Brewing System
- [ ] Implement vase brewing
- [ ] Barrel brewing with block detection
- [ ] Tank brewing via multiblock
- [ ] Distillery machine with processing logic

### 🔓 Unlocks
- [ ] Crafting-based progression (mead → wine → beer → spirits)
- [ ] Scrolls as unlock items
- [ ] Structure detection to spawn scrolls
- [ ] Scroll use triggers unlock + notification

### 📖 Recipe Book
- [ ] `/alcoholbook` command
- [ ] GUI menu with unlocked recipes only
- [ ] Click to view recipe details

### 🍻 Drunkenness System
- [ ] Drunkenness level tracker (per player)
- [ ] Effects: nausea, slowness, confusion
- [ ] Chat text transformation (slur, hiccups)
- [ ] Vomiting event (particles, sounds, item drops)
- [ ] Passing out mechanic (blackout or forced sleep)

### ✨ Polish & UX
- [ ] Config file for drinks, effects, brewing time
- [ ] Add brewing/vomit sounds and particles
- [ ] Permissions for commands and features
- [ ] Resource pack integration

---

## 📁 Suggested Folder Structure
drunken-brewing/
├── src/
│ └── main/
│ ├── BrewingManager.java
│ ├── AlcoholItem.java
│ ├── RecipeBookGUI.java
│ ├── DrunkennessManager.java
│ ├── UnlockManager.java
│ └── listeners/
│ ├── BrewingListener.java
│ ├── ChatListener.java
│ └── ScrollUnlockListener.java
├── resources/
│ ├── plugin.yml
│ └── config.yml


---

## 🗂 Future Ideas (Optional Features)
- Alcohol economy system (sell drinks)
- Brewing competition events
- Hangover system (penalties the next day)
- Alcohol shelf block (displays finished drinks)
- Integration with voice chat plugins (slurred voice effect)

---

## 💬 Commands

| Command | Description |
|--------|-------------|
| `/alcoholbook` | Open the player's recipe book |
| `/drunklevel` | Show current intoxication level |

---

## 🧪 Requirements

- Minecraft Java 1.17+
- PaperMC (recommended)
- Optional: Custom resource pack for models

---

## 🧠 License & Contributions

This plugin is under development and not yet licensed. Contributions, ideas, or feedback are welcome!

---
Author : 4Rust_CZ
Made with the help of Chatgpt

