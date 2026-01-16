# 🗺️ Zenith Roadmap

> **Philosophy:** "ช้าได้ แต่ห้ามห่วย"

## 📋 [C001] Coffee Dial-In Web App
**Created:** 2026-01-17
**Status:** ✅ COMPLETED
**Deploy:** GitHub Pages (https://vongsagon-git.github.io/coffee-tune/)

### Phase 1: Foundation
- [x] [C001.1] สร้าง HTML boilerplate + CDN links (Vue 3, Tailwind)
- [x] [C001.2] Setup Vue 3 app structure with reactive state
- [x] [C001.3] สร้าง Input Form (เบอร์บด, Dose, Yield, Time, TDS, Brix)
- [x] [C001.4] Implement computed values (Ratio, EY%)

### Phase 2: Extraction Chart
- [x] [C001.5] สร้าง SVG chart (แกน X = EY%, แกน Y = TDS%)
- [x] [C001.6] วาด zones (Perfect, Under, Over, Strong, Weak)
- [x] [C001.7] Plot จุดปัจจุบัน + history บน chart
- [x] [C001.8] แสดง arrow guide ไป Perfect Zone

### Phase 3: Recommendation Engine
- [x] [C001.9] Recommendation logic (Priority: เบอร์บด → เวลา → yield)
- [x] [C001.10] แสดงคำแนะนำ action-based

### Phase 4: Data & Storage
- [x] [C001.11] LocalStorage auto-save
- [x] [C001.12] Shot history + Confirm dialog
- [x] [C001.13] Export/Import JSON

### Phase 5: Deploy
- [x] [C001.14] Push to GitHub
- [x] [C001.15] Enable GitHub Pages

---

## 📋 [C002] Enhancements v6.1 - Smart Tuning
**Status:** ✅ COMPLETED
**Version:** 6.1

### Phase 1: Critical
- [x] [E001] Input validation (ป้องกัน edge cases)
- [x] [E001.1] Dose Fixed หลัง Shot แรก
- [x] [E001.2] Step-by-step tuning recommendation
- [x] [SMART] Smart Tuning UI

### Phase 2: Features (Removed in v6.5)
- [x] ~~[E002] Notes field~~ (ลบออก - ไม่จำเป็น)
- [x] ~~[E003] Rating stars~~ (ลบออก - ไม่จำเป็น)
- [x] ~~[E004] Flavor Tags~~ (ลบออก - ไม่จำเป็น)
- [x] [E005] Bean Name input

### Phase 3: v6.1 Improvements
- [x] [E006] Auto pre-fill recommended grind/yield
- [x] [E007] Session state persistence

---

## 📋 [C003] v6.2-6.5 - Native App + Starbucks Theme
**Status:** ✅ COMPLETED
**Version:** 6.5

### v6.2 Features
- [x] [E008] Copy Recipe feature
- [x] [E009] Recipe Library
- [x] [E011] Export All History as JSON
- [x] [E012] Import History from JSON
- [x] [E019] Bottom Navigation
- [x] [E020] Settings Page
- [x] [E021] Clear recommendation display

### v6.4 Smart Algorithm
- [x] [ALG001] Proportional Control (Kp * Error * Sensitivity)
- [x] [ALG002] Non-linear sensitivity (finer = more sensitive)
- [x] [ALG003] Flow rate diagnostic

### v6.5 Starbucks Theme + Fast Tuning
- [x] [UI001] Starbucks color palette (#006241, #F7F5F2)
- [x] [UI002] Sharp corners (no rounded)
- [x] [ALG004] Aggressive first shot (save coffee!)
- [x] [UX001] Purge reminder "บดทิ้ง 2-3g ก่อน"
- [x] [UX002] Keyboard shortcuts (Enter/Escape)

---

## 📋 [C004] Testing - Game Theory Analysis
**Status:** ✅ COMPLETED
**Report:** test.md

- [x] [TEST001] Input validation boundary tests (9/9 PASS)
- [x] [TEST002] EY calculation tests (3/3 PASS)
- [x] [TEST003] Algorithm logic verification
- [x] Pass Rate: 100%

---

## 📋 [C005] Future Backlog
**Status:** 🔮 FUTURE
**Priority:** Low

### Potential Features
- [ ] [E010] Share Recipe via URL/QR Code
- [ ] [E013] Dark/Light Theme Toggle
- [ ] [E014] Compare 2 shots side-by-side
- [ ] [E015] Shot Statistics (avg EY, avg TDS, best shot)
- [ ] [E016] Haptic feedback on mobile
- [ ] [E017] Swipe to delete shot from history

---

## 📊 Research Verified
- [x] EY% formula: (Yield × TDS%) / Dose
- [x] Perfect Zone: EY 18-22%, TDS 8-12% (SCA Standards)
- [x] Proportional Control theory applied to grind adjustment
- [x] Starbucks brand colors: #006241, #00754A, #D4E9E2

---

## 🗂️ Archive - Completed Versions
**Live URL:** https://vongsagon-git.github.io/coffee-tune/
**Current Version:** 6.5 Starbucks Theme

| Version | Features | Date |
|---------|----------|------|
| v5.0 | Dark Theme, Inter font, Glass UI | 2026-01-17 |
| v6.0 | PWA, Chart, Flavor, 6 inputs | 2026-01-17 |
| v6.1 | Smart Tuning, Auto pre-fill | 2026-01-17 |
| v6.2 | Native App, Bottom Nav, Recipes | 2026-01-17 |
| v6.4 | Smart Algorithm, Feedback Loop | 2026-01-17 |
| v6.5 | Starbucks Theme, Fast Tuning | 2026-01-17 |

