# BE ZEN – MVP v4 (Deployable)

אפליקציית ווב סטטית בקובץ אחד. כך תפרסו אותה ב‑1–3 דקות, בלי שרת:

## אפשרות 1: GitHub Pages
1) צרו ריפו חדש ב‑GitHub (Public).
2) העלו את `index.html` ו־`404.html` (או את כל ה‑ZIP).
3) Settings → Pages → Deploy from a branch → Source: main / (root).
4) הכתובת תעבוד אחרי ~דקה: `https://<username>.github.io/<repo>`.

## אפשרות 2: Netlify (Drag & Drop)
1) כנסו ל־https://app.netlify.com/drop
2) גררו את התיקייה `bezen_mvp_v4_deployable` (או ה‑ZIP).
3) קבלו דומיין מיידי, ניתן לשינוי.

## אפשרות 3: Vercel
1) Import Git → בחרו את הריפו מהאפשרות הראשונה.
2) Framework: Other; Output: `/`.
3) Deploy.

### קבצים
- `index.html` – האפליקציה (v4).
- `404.html` – דף ברירת מחדל לניווט.
- `netlify.toml` – הגדרות Netlify.
- `vercel.json` – הגדרות Vercel.

> אין תלות חיצונית. כל פלטפורמת Static Hosting תעבוד.