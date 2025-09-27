### Shards of Aether

*“Gather the fragments of the heavens, and rebuild a world torn apart.”*

---

## 🌌 Introduction
**Shards of Aether** is a 2D action RPG with sandbox elements, inspired by *Minecraft*, *Skyrim*, *Kingdoms of Amalur*, and *Warframe*.  
Players explore a shattered skyworld made of floating islands, battling enemies, collecting resources, and uncovering the mystery behind the broken heavens.  

---

## 🌍 World Layout
The world is centered around a **Hub Island** that acts as the player’s home base. Surrounding it are different island types:

- **Hub/Base Island**  
  - Crafting station  
  - Player home  
  - NPCs with quests  

- **Resource Islands**  
  - *Forest* (wood + herbs)  
  - *Stone Quarry* (stone + ore)  
  - *Crystal Island* (mana crystals)  

- **Enemy Islands**  
  - *Slime Swamp* (basic melee enemies)  
  - *Bat Cave* (flying enemies)  

- **Dungeon Islands**  
  - *Corrupted Temple* (mini-boss + shard)  
  - *Sky Ruins* (major boss + shard)  

---

## 🗺 ASCII Map Layout

[Dungeon Island: Sky Ruins]
                          (Boss)
                            |
         [Resource: Crystal Island]---[Enemy: Bat Cave]
                            |

[Resource: Forest]----[Hub/Base Island]----[Resource: Stone Quarry] | [Enemy: Slime Swamp] | [Dungeon Island: Corrupted Temple]

---

## ⚔️ Gameplay Loop
1. Start at **Hub Island** → prepare gear.  
2. Travel to **Resource Islands** → collect materials.  
3. Fight through **Enemy Islands** → earn XP + loot.  
4. Upgrade gear & skills at the hub.  
5. Enter **Dungeon Islands** → defeat bosses → collect *Shards of Aether*.  
6. Unlock new rings of islands as progression continues.  

---

## 🎮 Player Features
- **Movement** → walk, jump, dash, wall climb (later unlocks).  
- **Combat** → light/heavy attacks, dodge roll, combo chaining.  
- **Progression Paths**:  
  - *Warrior* (swords, shields, tanky).  
  - *Rogue* (fast, mobility, stealth).  
  - *Mage* (ranged magic, mana resource).  

---

## 🎨 UI Layout
- **Top Left** → Health + Stamina bars.  
- **Top Right** → Inventory count (resources).  
- **Bottom Center** → Quickbar (weapons/tools).  
- **Pause Menu** → Quests, Crafting, Settings.  

---

## 📖 Story & Lore
Long ago, the heavens shattered, and fragments of divine energy known as **Aether Shards** scattered across the skies.  
These shards now power both the islands and the monsters that roam them.  
The player must gather the shards to restore balance — or risk the world collapsing further into chaos.  

---

## ✅ MVP (First Playable Build)
To keep scope small and achievable:  

- 1 Hub Island (crafting + NPC).  
- 3 Resource Islands (forest, stone, crystal).  
- 2 Enemy Islands (slime swamp, bat cave).  
- 1 Dungeon Island (mini-boss fight).  
- Basic UI (health, inventory, quickbar).  

---

## 🛠️ Tech & Tools
- **Engine**: Godot 4 (2D only, lightweight).  
- **Language**: GDScript (with Neovim as editor).  
- **Art**: Pixel art (Piskel or Aseprite).

