**Project Title:** Valorant Game Testing
**Module:** User Interface (HUD)
**Test Type:** UI Testing

---

### 🐞 Bug ID: VAL-002

**Title:** Minimap does not update player position correctly after respawn

---

### 🔍 Description:

After respawning, the minimap occasionally displays the player at the previous death location instead of the current position.

---

### 🔁 Steps to Reproduce:

1. Start a match
2. Move to a different area of the map
3. Get eliminated
4. Respawn
5. Observe minimap position

---

### ✅ Expected Result:

Minimap should update instantly to reflect the player’s current position after respawn

---

### ❌ Actual Result:

Minimap shows outdated position for a few seconds

---

### 🎯 Severity: Medium

(UI confusion but not game-breaking)

### ⚠️ Priority: Medium

---

### 🖥️ Environment:

* Platform: PC
* Mode: Deathmatch / Practice

---

### 💡 Notes:

* Likely delay in UI refresh or sync issue with server data
