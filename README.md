# Portfolio — مصمّم جرافيك

ملف أعمال احترافي (12 صفحة، A4 أفقي) جاهز للإرسال للعملاء.

- `Portfolio-Graphic-Designer-AR.pdf` — الملف النهائي
- `portfolio.html` — المصدر القابل للتعديل
- `assets/fonts/` — خطوط Cairo / Tajawal / Inter / Playfair (OFL)

## إعادة التصدير بعد التعديل

```bash
chromium --headless --no-pdf-header-footer --virtual-time-budget=8000 \\
  --print-to-pdf=Portfolio-Graphic-Designer-AR.pdf portfolio.html
```

> استبدل الحقول بين `[ ]` (الاسم، الهاتف، البريد، بيهانس، إنستغرام) ببياناتك، واستبدل أسماء المشاريع والأرقام بأعمالك الحقيقية.
