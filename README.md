---

##💬 Note: All scripts are written using temporary code, stored in mudlet.storage and will not show up in your mudlet triggers/aliases/keys/... I really hate clutter. Info on scripts shows up when script loads in echoes. **  

##💬These are my characters:
Zygmud          (18) Rawr, Eladamri, Tiamat, Djinn, Balur, Ezuri, Guust, Larian, Median, Starke, 
                     Swag, Taki, Wicyth, Bamm, Dalinar, Tusker, Zygmud, celebrindor ** 

---

## 🗂️ File Descriptions

| File | Description |
|------|-------------|
| `AutoAssist.mpackage` | Autoassist. Follow sets leader, when anything happens to leader in combat, assists. F1 turns it on and off. (BUGGED: Regexes don't capture all combat messages)|
| `AzraZaira.mpackage` | Sets 'azra' alias after looking at the star map. Type azra to execute correct commands to open door. |
| `BlindSequence.mpackage` | Blinds targets in sequence, forward or backwards. Tired of blinding 23.spirit? This helps. |
| `EQViewer.mpackage` | Sets links on equipment and shop into. On equipment there are links for the item and the slot. When clicked, the item and shop info will open up a miniconsole with the ID information for the item formatted nicely. Equipment item matching is exact, shop item is fuzzy, and can possibly cause mismatches. I've checked most, and have found little to no problems. Please inform me in-game if you find any incorrect links. On the equipment slot, the console will show all available items for that slot, along with their stats. REQUIRES THE JSON DATABASE TO EXECUTE. Place the "mume_items.json" in your mume profile folder in mudlet.|
| `FriendTracker.mpackage` | Who's who of the mume world. Ties characters to a nickname, then shows that nickname in who/group, if a friend is playing a character. Can also show the entire DB. Loads a file called "friend_char_list.json" in your mume profile folder in mudlet. Either put existing database there, or start from scratch |
| `MassEnchanting.mpackage` | Enchant arrows, bolts, whatever. Bulk enchanting. Go afk, but don't forget to feed yourself. |
| `MumeKeySubstitutions.mpackage` | Labels for keys. |
| `OldschoolTwiddlers.mpackage` | New twiddlers suck! This returns oldschool twiddlers and adds execution time. |
| `StatusBar_SpellTimers.mpackage` | Addon for Khazdul's spelltimer package, found here: https://github.com/Khazdul/MUME. It uses his timer database to put a simple bar at the bottom that shows the time, for better viewing. Also FLASHES BRIGHT RED if your big spells drop. |
| `TPTracker.mpackage` | GMCP TP tracker. Shows TP when you gain them ingame. Manual command included to check since last request. |
| `XPTracker.mpackage` | GMCP XP tracker. Gives pretty overview of what xp you gained this session. More of the data can be shown if wanted. WILL NOT WORK IF INSTALLED MIDSESSION (or will only start working next true login). REQUIRES GMCP INFO THAT IS ONLY PASSED AT LOGIN. INSTALL FIRST, THEN LOGIN TO MUME.|

---

## ⚙️ Installation

1. Download the `.mpackage` files from this repository.  
2. In Mudlet: Toolbox->Package Manager->Install new package, select mpackage

---

## 🧩 Customization

Each `.mpackage` file can be customized:
- Open the file in a text editor or module editor.
- Adjust script.
- Don't contact me if shit breaks.

---

