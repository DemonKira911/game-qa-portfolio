**Project Title:** Valorant Game Testing
**Module:** Performance
**Test Type:** Performance Testing

---

### 🐞 Bug ID: VAL-003

**Title:** Frame drop observed during multiple ability usage in close proximity

---

### 🔍 Description:

Significant FPS drop occurs when multiple abilities are used simultaneously in a confined area.

---

### 🔁 Steps to Reproduce:

1. Enter a match with multiple players
2. Use abilities simultaneously (smokes, flashes, explosives)
3. Observe FPS performance

---

### ✅ Expected Result:

Game should maintain stable FPS without major drops

---

### ❌ Actual Result:

FPS drops significantly causing lag and input delay

---

### 🎯 Severity: High

(Affects gameplay responsiveness)

### ⚠️ Priority: High

---

### 🖥️ Environment:

* Platform: PC
* GPU: Mid-range (assumed)
* Mode: Competitive / Team fights

---

### 💡 Notes:

* Could be due to particle rendering overload
* Needs optimization for multiple effects
