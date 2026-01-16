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
**Priority:** High
**Version:** 6.1

### Phase 1: Critical
- [x] [E001] Input validation (ป้องกัน edge cases - ค่าติดลบ, ค่าเกิน, null) ✅
- [x] [E001.1] Dose Fixed หลัง Shot แรก (กรอกครั้งเดียว) ✅
- [x] [E001.2] Step-by-step tuning recommendation ✅
- [x] [SMART] Smart Tuning UI (Progress bar, Visual hints, Clear instructions) ✅

### Phase 2: Nice to Have
- [x] [E002] Notes field (บันทึกโน้ตแต่ละ shot) ✅
- [x] [E003] Rating stars (1-5 ดาว) ✅
- [x] [E004] Flavor Tags (เลือกรสชาติที่ชิมได้) ✅
- [x] [E005] Bean Name input (ระบุชื่อเมล็ดกาแฟ) ✅

### Phase 3: v6.1 Improvements
- [x] [E006] Auto pre-fill recommended grind/yield ✅
- [x] [E007] Session state persistence (refresh safe) ✅

---

## 📊 Research Verified
- [x] EY% formula: (Yield × TDS%) / Dose ✅
- [x] Perfect Zone: EY 18-22%, TDS 8-12% (SCA Standards) ✅

---

## 📋 [C003] v6.2 - Native App Experience
**Status:** ✅ COMPLETED
**Created:** 2026-01-17

### 🧘 Discovered During Enlightenment
- [x] [E008] Copy Recipe feature (คัดลอกสูตรเมื่อ Perfect) ✅
- [x] [E009] Recipe Library (เก็บสูตรที่ Perfect ไว้ใช้ภายหลัง) ✅
- [x] [E011] Export All History as JSON ✅
- [x] [E012] Import History from JSON ✅
- [x] [E019] Bottom Navigation (Native App Style) ✅
- [x] [E020] Settings Page ✅
- [x] [E021] Clear recommendation display (same vs change) ✅

### 📋 Backlog (Future)
- [ ] [E010] Share Recipe via URL/QR Code
- [ ] [E013] Dark/Light Theme Toggle
- [ ] [E014] Compare 2 shots side-by-side
- [ ] [E015] Shot Statistics (avg EY, avg TDS, best shot)

### 🔍 UX Improvements (Future)
- [ ] [E016] Haptic feedback on mobile (vibrate on save)
- [ ] [E017] Swipe to delete shot from history
- [ ] [E018] Keyboard shortcuts (Enter to analyze)

---

## 🗂️ Archive - Completed
**Live URL:** https://vongsagon-git.github.io/coffee-tune/
**Version:** 6.1 Smart Tuning
