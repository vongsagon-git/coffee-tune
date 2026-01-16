# 🗺️ Zenith Roadmap

> **Philosophy:** "ช้าได้ แต่ห้ามห่วย"

## 📋 [C001] Coffee Dial-In Web App
**Created:** 2026-01-17
**Status:** In Progress
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

## ✅ COMPLETED
**Live URL:** https://vongsagon-git.github.io/coffee-tune/

---

## 📋 [C002] Enhancements (จาก Self-Check)
**Status:** Pending
**Priority:** Medium

- [ ] [C002.1] เพิ่ม Flavor Wheel component (เลือกรสชาติที่ชิมได้)
- [ ] [C002.2] เพิ่ม Notes field (บันทึกโน้ตเพิ่มเติม)
- [ ] [C002.3] เพิ่ม Rating stars (ให้คะแนน 1-5 ดาว)
- [ ] [C002.4] เพิ่ม Input validation (ป้องกัน edge cases)
- [ ] [C002.5] เพิ่ม Batch/Bean tracking (แยกตามเมล็ดกาแฟ)
