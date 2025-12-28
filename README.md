# 🎲 Ludic Project

![Status](https://img.shields.io/badge/Status-Pre--MVP_Alpha-orange) ![Platform](https://img.shields.io/badge/Platform-Android-green)

> **Note:** Formerly known as [*Gamicraft*](https://github.com/kyuris8931/Gamicraft-Project). Ludic Project is a Gamification RPG designed to turn your life progress into a chaotic, strategic battle experience.

## 📖 About The Game
Ludic Project isn't just a To-Do list. It's a full-fledged RPG with a unique **"Pseudo-Position"** battle system where speed doesn't exist—position is everything.

Connect your real-life achievements (via API/DeepLink) to power up your Main Character, summon heroes, and survive the chaos.

## ✨ Key Features

### ⚔️ Chaos Battle System (The Core)
* **Pseudo-Positioning:** The turn order *is* the map. If an enemy is next in the turn order, they are physically "1 tile" away from you.
* **Round Shuffle:** Every new round, the unit order is completely randomized. Adapt or die.
* **Main Character Deck:** Your MC doesn't have fixed skills. Instead, they pull **3 Random Skills** from your unlocked pool every turn. Used skills go on real-time cooldown.
* **Infinite Scale:** The visual engine supports unlimited units (100 vs 100 battles are possible!).
* **Tactical End-Turn:** Tap 3 times to pass your turn strategically to manipulate the timeline.

### 💰 Economy & Progression
* **Escalation Price:** Gold prices for items increase with every purchase to prevent hoarding, resetting daily.
* **Gacha Protocol:** * **Pity System:** Guaranteed SSR after 100 summons.
    * **SR Guarantee:** On every 10x bulk summon.
* **Hero Fatigue:** Heroes have cooldowns after battle. You must manage a wide roster of units, not just one strong team.

### 🛠️ The Workshop (Catalog)
A comprehensive creation suite separated into tiers:
1.  **Creation:** Make your own Items, Enemies, and Skills.
2.  **Official:** Content provided by developers.
3.  **Community:** Curated content from other players.
4.  **Supporter:** Exclusive branded items/heroes.

### 🔗 Connectivity (LifeRPG Integration)
Ludic Project exposes a DeepLink API to sync with your life:
* **Import Progress:** Transfer EXP, Gold, and Diamonds from external productivity apps.
* **Export Actions:** Using an item in-game can trigger a generic Android Broadcast (perfect for Tasker/MacroDroid automations).

## 📱 Visuals & Gameplay
* **Dynamic Targets:** The UI dynamically highlights valid targets based on your Skill Range relative to the Pseudo-Position queue.
* **Enemy Composition:** Visuals support displaying Bosses, Elites, and Minions distinctly.
* **Scrollable Battlefield:** Peek ahead in the turn order to plan your strategy.

## 🚀 Roadmap (Pre-MVP)
- [x] **Pseudo-Position Engine:** Linear queue battle logic.
- [x] **Economy:** Shop with inflation logic & Gacha.
- [x] **Connectivity:** DeepLink receiver & Broadcast sender.
- [x] **Visuals:** Different pose for IDLE/ATTACK/HURT states.
- [ ] **Talent System:** Unique kits for every ally unit.
- [ ] **Ultimate Gauge:** Special moves implementation.

---
*Ludic Project is currently in active development. Download the latest Alpha build in the Releases tab.*
