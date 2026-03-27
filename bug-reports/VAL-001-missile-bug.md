# 🐞 VAL-001 – Missile Ability Bug

**Game:** Valorant
**Module:** Agent Ability System
**Severity:** High
**Priority:** High

---

## 🔍 Description

Agent ability fires 3 missiles instead of intended 2, causing gameplay imbalance.

---

## 🔁 Steps to Reproduce

1. Launch game
2. Select agent "Tejo"
3. Activate ability (E)
4. Select 2 missiles, move back and add another
5. Launch ability

---

## ✅ Expected Result

Only 2 missiles should be fired

---

## ❌ Actual Result

3 missiles are fired

---

## 💡 Notes

* Possible input duplication issue
* Could be ability stacking bug
