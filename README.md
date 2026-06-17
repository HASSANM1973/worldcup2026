# World Cup 2026 - كأس العالم 2026

Live World Cup 2026 companion app — schedule, standings, knockout bracket, and legal watch options. Dual language (EN/AR).

تطبيق مصاحب لكأس العالم 2026 — جدول المباريات، الترتيب، شجرة الإقصائيات، وخيارات المشاهدة القانونية. يدعم اللغتين الإنجليزية والعربية.


## Features | المميزات

- **Today's Matches** — matches happening today with flag images | مباريات اليوم مع أعلام الفرق
- **Full Schedule** — filter by group/knockout/finished/live/search | جدول جميع المباريات مع فلترة وبحث
- **Live Standings** — computed from match results (MP, W, D, L, GF, GA, GD, PTS) | ترتيب المجموعات محسوب من النتائج
- **Knockout Bracket** — R32 → R16 → QF → SF → 3rd → Final | شجرة الإقصائيات
- **Legal Watch** — official FIFA-authorized broadcasters worldwide | روابط المذيعين الرسميين
- **Dual Language** — toggle between English and Arabic | تبديل بين الإنجليزية والعربية
- **Auto-refresh** — live data every 60 seconds | تحديث تلقائي كل 60 ثانية
- **Responsive** — works on mobile, tablet, desktop | متجاوب مع جميع الأجهزة

## Live Demo | تجربة مباشرة

[https://hassanm1973.github.io/worldcup2026/](https://hassanm1973.github.io/worldcup2026/)

## Tech Stack | التقنيات

- Pure HTML / CSS / JavaScript (single-file app)
- No frameworks, no build tools, no dependencies
- Hosted on GitHub Pages (free HTTPS)
- Data source: [worldcup26.ir](https://worldcup26.ir) (free API, no key required)

## Files | الملفات

| File | Description |
|------|-------------|
| `index.html` | Single-file app (all CSS + JS embedded) |
| `logo.png` | App logo |
| `server.js` | Local dev server (not needed for GitHub Pages) |

## Run Locally | التشغيل المحلي

```bash
node server.js
# Open http://localhost:3000
```

Or just open `index.html` directly in a browser.

## License

All rights reserved Academic Coding 2026
