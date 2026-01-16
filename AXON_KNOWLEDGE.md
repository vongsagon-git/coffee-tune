# 💎 Zenith Knowledge Vault

> บันทึกเฉพาะสิ่งที่ **"ตกผลึกแล้ว"** และ **"ใช้งานได้จริง"**

---

## Coffee Extraction Knowledge

---
id: coffee-extraction-formula
tags: [coffee, espresso, extraction]
credibility: 95%
last_verified: 2026-01-17
---

### สูตรคำนวณ Extraction Yield

```
EY% = (Yield × TDS%) / Dose

ตัวอย่าง:
- Dose: 18g, Yield: 36g, TDS: 10%
- EY% = (36 × 10) / 18 = 20%
```

### Perfect Zone (Espresso)
| Parameter | Range | รสชาติ |
|-----------|-------|-------|
| EY% | 18-22% | หวาน, balanced |
| TDS% | 8-12% | เข้มพอดี |

### Zone Colors
| Zone | EY% | TDS% | Color | รสชาติ |
|------|-----|------|-------|-------|
| Perfect | 18-22 | 8-12 | 🟢 | หวาน balanced |
| Under | <18 | any | 🟡 | เปรี้ยว จืด |
| Over | >22 | any | 🔴 | ขม astringent |
| Strong | any | >12 | 🟠 | เข้มเกิน |
| Weak | any | <8 | ⚪ | จืด watery |

---
id: dial-in-priority
tags: [coffee, dial-in, adjustment]
credibility: 90%
last_verified: 2026-01-17
---

### ลำดับการปรับค่า (Appia Life XT - 12 bar)

```
1️⃣ เบอร์บด (Grind Size) - ปรับเป็นหลัก
   - EY ต่ำ → บดละเอียดขึ้น (เลขลด)
   - EY สูง → บดหยาบขึ้น (เลขเพิ่ม)

2️⃣ เวลา (Time) - รองลงมา
   - Time < 20s + EY ต่ำ → บดละเอียดกว่านี้
   - Time > 35s + EY สูง → บดหยาบกว่านี้

3️⃣ Yield - ท้ายสุด (ปรับ TDS)
   - TDS > 12% → เพิ่ม yield
   - TDS < 8% → ลด yield
```

### Equipment Notes
- **Appia Life XT:** Fixed 12 bar (สูงกว่าปกติ 9 bar)
- **F64 Evo Pro:** Scale 1.1 - 12.0

---
id: vue3-cdn-pattern
tags: [vue, cdn, frontend]
credibility: 95%
last_verified: 2026-01-17
---

### Vue 3 CDN Pattern (No Build)

```html
<script src="https://unpkg.com/vue@3/dist/vue.global.prod.js"></script>
<script src="https://cdn.tailwindcss.com"></script>

<script>
const { createApp, ref, computed, watch, onMounted } = Vue

createApp({
  setup() {
    const state = ref({})
    const computed1 = computed(() => ...)

    return { state, computed1 }
  }
}).mount('#app')
</script>
```

### ข้อดี CDN Only
- ไม่ต้อง build/webpack
- Double-click เปิดได้เลย
- Deploy ง่าย (ไฟล์เดียว)

---
id: github-pages-deploy
tags: [github, deploy, hosting]
credibility: 95%
last_verified: 2026-01-17
---

### GitHub Pages Deployment

1. Push `index.html` ไป GitHub repo
2. Settings → Pages → Deploy from branch
3. เลือก `main` → `/ (root)` → Save
4. รอ 1-2 นาที → ได้ URL

**URL Pattern:** `https://[username].github.io/[repo]/`
