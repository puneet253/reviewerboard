# Puneet Portfolio (GitHub Pages Ready)

Agar `http://puneet253.github.io/puneetportfolio/` par 404 aa raha hai, to usually issue GitHub Pages settings ka hota hai. Neeche exact fix diya hai.

## ✅ Sahi live URL (HTTP nahi, HTTPS use karo)

Use this:

- `https://puneet253.github.io/puneetportfolio/`

> `http://` par kabhi-kabhi redirect/404 issue aa sakta hai, isliye direct `https://` open karo.

## 1) Confirm repo name exactly same hai

GitHub me repo ka naam **exactly** ye hona chahiye:

- `puneetportfolio`

Agar repo ka naam alag hai (jaise `PuneetPortfolio` ya `portfolio`), URL bhi उसी हिसाब se change hoga.

## 2) Code `main` branch me hona chahiye

Repo ke root me ye files honi chahiye:

- `index.html`
- `styles.css`
- `script.js`

Agar local se push karna hai:

```bash
git remote add origin https://github.com/puneet253/puneetportfolio.git
git branch -M main
git add .
git commit -m "portfolio setup"
git push -u origin main
```

## 3) GitHub Pages enable karo (most important)

1. Repo open karo: `https://github.com/puneet253/puneetportfolio`
2. Jao: **Settings → Pages**
3. **Build and deployment** me set karo:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
4. **Save** karo.

## 4) Deployment status check karo

Settings → Pages me message aana chahiye:

- “Your site is live at `https://puneet253.github.io/puneetportfolio/`”

First deploy ko 2–10 min lag sakte hain. Uske baad page hard refresh karo:

- Windows/Linux: `Ctrl + Shift + R`
- Mac: `Cmd + Shift + R`

## 5) Agar phir bhi 404 aa raha hai

Ye 5 cheeze check karo:

1. Repo **public** hai (private repo me Pages limits ho sakti hain plan ke hisaab se).
2. `index.html` root me hai, kisi subfolder me nahi.
3. Pages source `main` + `/root` selected hai.
4. URL me typo nahi hai: `puneet253.github.io/puneetportfolio/`
5. Browser cache clear/hard refresh kiya.

## 6) Quick update workflow

```bash
git add .
git commit -m "update portfolio"
git push
```

Push ke baad 1-2 min me live site update ho jayegi.
