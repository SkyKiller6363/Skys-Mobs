# Geomancer Boss Pack

**Requirements**
- ✅ **MythicMobs** free 5.8+  
- ✅ **LibsDisguises** free (latest version)  
- ⚠️ **Optional:** Mythic Crucible 2.2+ — only needed for custom pack generation and item-based skills  

---

## Overview

*Inspired by Minecraft Dungeons,* the **Geomancer** boss transforms the battlefield! Expect basalt pillars to erupt in your path, summoned minions fighting from between the cracks, and elemental attacks to keep you on your toes. Suitable for solo play and designed for easy–medium difficulty levels.

---

## Key Features

- **1 Boss + 5 Minions:** A fully fleshed-out boss encounter with plenty of action.
- **7 Dynamic Skills:** Includes pillar generation, soul-flame projectiles, and charged lightning circles.
- **Summoning Mechanics:** Basalt pillars disrupt movement, giving minions room to attack.
- **Elemental Attacks:**
  - **Lightning Circles** that charge before striking.
  - **Soul-Flame Projectiles** that home in on the player.
- **5 Custom Items:**  
  Includes 2 unique items with special skills, plus a **Voodoo Doll** — a totem of undying with a custom modeled texture.

---

## Mythic Mobs Pack Installation Instructions

1. **Download the Geomancer Pack**  
   Click [here](https://downgit.github.io/#/home?url=https://github.com/SkyKiller6363/Skys-Mobs/new/main/Packs/Geomancer) to download all files. Then extract the `MythicMobs/Geomancer` folder from the pack download.

2. **Upload to Server**  
   Place the `Geomancer` folder into `plugins/MythicMobs/Packs` on your server.

3. **MythicMobs Reload**  
   Run `/mm reload` to register the pack.

---

## Disguise Setup (LibsDisguises)

You have two options:

- **Option 1 – Copy Disguise Entry:**  
  Copy the `Geomancer:` line from the provided `disguises.yml` and paste it into your server’s LibsDisguises file.

- **Option 2 – Use Provided Skin File:**  
  1. Drop `Geomancer.png` into your server’s `LibsDisguises/skins` folder.  
  2. In-game, execute:  
     ```
     /savedisguise Geomancer player <inherit> setSkin Geomancer.png setDynamicName
     ```
  3. Run `/mm reload` so the disguise is applied.

---

## Voodoo Doll & Custom Resource Pack

**If you're not using Mythic Crucible:**  
- Manually add the model and texture found in `Packs/Geomancer/Assets` to your resource pack.

**If you're using Mythic Crucible:**  
1. Run `/mm reload`  
2. Then run `/mm i generate`  
3. Locate the generated pack at `MythicMobs/Generation/Resource_Pack.zip`  
4. Import it into your resource pack manager or manually add to your Minecraft Client.

---

## Enjoy the Show!

The Geomancer Boss Pack offers a thrilling, action-packed experience straight out of the cave. Whether scheduling epic solo fights or adding new challenges to your server, this boss brings adventure to life.  

**Let me know if you’d like help tweaking any settings or using the pack!**
