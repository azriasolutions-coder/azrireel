# AzriReel Pro

> מערכת מתקדמת ליצירת סרטוני וידאו — עם כלי AI אינטגרטיביים.

פלטפורמה מקצועית לסרטוני Reels אנכיים, אופקיים וריבועיים, עם ספריית מעברים עשירה, פילטרים קולנועיים, ורוד-מפה ל-AI עתידי (בחירת מוזיקה חכמה, סנכרון לקצב, חיתוך חכם, ועוד).

## תכונות עיקריות

- 🎞️ **39 אפקטי מעבר** (fade, slide, circle, radial, zoomin, ועוד)
- 🎨 **9 פילטרים קולנועיים** — Cinematic, Warm, Cool, Vintage, Sepia, Vivid, Noir, Sparkle
- 📐 **7 גדלי וידאו** — 9:16, 1:1, 4:5, 3:4, 16:9 (כולל HD ו-Full HD)
- 📌 **הצמדת מיקומים** — fix specific positions, shuffle the rest
- 🖼️ **רקע מותאם** — תמונה או וידאו מאחורי הסצנות
- 🎵 **בחירת מוזיקה** + העלאה
- 🎬 **תמונות + קליפים יחד**
- 🤖 **כרטיס AI features** (בפיתוח) — בחירת שיר חכמה, סנכרון ביט, חיתוך saliency, כתוביות, גריידינג, upscale, טקסט אוטומטי, קריינות

## דרישות

- Python 3.10+
- ffmpeg ב-PATH

## הפעלה מקומית

```bash
pip install -r requirements.txt
python -m web.server
# → http://127.0.0.1:5058
```

## CLI

```bash
python cli.py /path/to/images -o output.mp4 \
  --transition auto --look cinematic --aspect 9:16
python cli.py --list-transitions
```

## פריסה

ראה `DEPLOY.md`. `Dockerfile` + `render.yaml` מוכנים.

---

<div align="center">

**מבית [AzriaSolutions](https://azriasolutions.com)** · [054-566-0226](tel:+972545660226)

</div>
