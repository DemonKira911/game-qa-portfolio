**Project Title:** Valorant Game Testing
**Module:** Input Handling
**Test Type:** Edge Case Testing

---

### 🐞 Bug ID: VAL-005

**Title:** Ability triggers twice when key is spammed rapidly

---

### 🔍 Description:

Rapidly pressing the ability key sometimes triggers the ability twice, consuming extra resources.

---

### 🔁 Steps to Reproduce:

1. Select any agent
2. Rapidly press ability key multiple times
3. Observe ability behavior

---

### ✅ Expected Result:

Ability should trigger only once per valid input

---

### ❌ Actual Result:

Ability triggers multiple times inconsistently

---

### 🎯 Severity: Medium

### ⚠️ Priority: Medium

---

### 🖥️ Environment:

* Platform: PC
* Input: Keyboard

---

### 💡 Notes:

* Likely missing input debounce handling
