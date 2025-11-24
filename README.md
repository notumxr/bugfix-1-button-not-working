# 🐞 Bug Fix #1 — Button Not Working (JavaScript Event Listener Bug)

## 🔧 Problem
The button did not respond when clicked because the JavaScript code used incorrect method names.

### ❌ Broken Issues
- `getElementByID()` → incorrect (case-sensitive)
- `addEventlistener()` → incorrect (capital "L" missing)
- Event listener never attached → button did nothing

---

## ✅ Fixed Code Changes
- Corrected to `getElementById()`
- Corrected to `addEventListener()`
- Verified the button now displays an alert when clicked

---

## 📁 Files in This Bug Fix
- `broken/bug1.html` — original broken version
- `fixed/bug1_fixed.html` — corrected working version
- `README.md` — explanation of the bug and fix

---

## ✔️ Status
**Fixed and tested.**