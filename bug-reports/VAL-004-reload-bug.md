**Project Title:** Valorant Game Testing
**Module:** Weapon System
**Test Type:** Functional Testing

---

### 🐞 Bug ID: VAL-004

**Title:** Reload animation completes but weapon remains empty

---

### 🔍 Description:

After completing reload animation, the weapon sometimes shows zero ammo and cannot fire.

---

### 🔁 Steps to Reproduce:

1. Fire all bullets from weapon
2. Press reload
3. Immediately switch weapon and switch back
4. Attempt to fire

---

### ✅ Expected Result:

Weapon should reload successfully and allow firing

---

### ❌ Actual Result:

Weapon shows empty magazine despite reload animation completion

---

### 🎯 Severity: High

(Core gameplay functionality affected)

### ⚠️ Priority: High

---

### 🖥️ Environment:

* Platform: PC
* Mode: Any

---

### 💡 Notes:

* Possible state sync issue between animation and ammo logic
