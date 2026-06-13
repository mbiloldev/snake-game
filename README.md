# 🐍 Snake O'yini

> Klassik arkada o'yini — HTML5 Canvas va JavaScript bilan yaratilgan

---
<div align="center">
  <img src="./banner.svg" width="100%"/>
</div>

## 📖 Loyiha haqida

Snake — ilonni boshqarib ovqat yeydigan klassik o'yin. Har yutgan ovqat bilan ilon uzayadi va tezlashadi. Devorga yoki o'z dumiga tegsa — o'yin tugaydi!

---

## ✨ Xususiyatlar

- 🎮 Silliq 17×17 katakli o'yin maydoni
- 👀 Ilon ko'zlari — bosh qaysi tomonga qarasa ko'rinadi
- ⚡ Ovqat yegan sari tezlashib boradi
- 🏆 Ball va rekord hisoblagichi
- ⌨️ Klaviatura (o'q tugmalar) bilan boshqarish
- 📱 Telefonda swipe va D-pad tugmalari
- 💥 O'yin tugaganda silkinish animatsiyasi
- 🌑 Ko'zga qulay qorong'u fon

---

## 🕹️ Boshqarish

### Kompyuter (klaviatura)
| Tugma | Harakat |
|-------|---------|
| `↑` | Yuqoriga |
| `↓` | Pastga |
| `←` | Chapga |
| `→` | O'ngga |

### Telefon / planshet
- **Swipe** — ekranda istalgan tomonga suring
- **D-pad** — ekrandagi `↑ ↓ ← →` tugmalar

---

## ⚙️ Texnik tafsilotlar

### Texnologiyalar
| Texnologiya | Maqsad |
|-------------|--------|
| HTML5 Canvas | O'yin maydoni va grafika |
| Vanilla JavaScript | O'yin mantiqi |
| CSS3 | Dizayn va animatsiyalar |
| `setInterval()` | O'yin sikli |

### Fayl tuzilmasi
```
snake_game.html   ← asosiy fayl (CSS + JS hammasi ichida)
README.md         ← shu fayl
```

### O'yin parametrlari
```javascript
const COLS = 17        // Ustunlar soni
const ROWS = 17        // Qatorlar soni
const CELL = 20        // Katak o'lchami (px)
let speed = 130        // Boshlang'ich tezlik (ms)

// Tezlashuv formulasi:
speed = Math.max(60, 130 - score * 5)
```

---

## 🚀 Ishga tushirish

Hech qanday o'rnatish talab qilinmaydi!

```bash
# Shunchaki brauzerda oching:
open snake_game.html
```

**Brauzer talablari:** Chrome 80+ · Firefox 75+ · Safari 13+ · Edge 80+

---

## 🏅 Ball tizimi

| Holat | Ball |
|-------|------|
| Har bir ovqat | +1 |
| Rekord | Sessiyada saqlanadi |
| Sahifa yangilanса | Nolga tushadi |

---

## 📄 Litsenziya

MIT License — erkin foydalanishingiz mumkin.

---

<p align="center">🐍 <i>Claude (Anthropic) tomonidan yaratilgan · 2025</i></p>
