# Puneet Portfolio (GitHub Pages Setup)

Aap abhi galat screen par ho: **"Pages / Add a verified domain"**.
Waha domain tabhi add hota hai jab aapke paas apna खरीदा हुआ custom domain ho (jaise `example.com`).
`puneet253.github.io/puneetportfolio` custom domain nahi hai.

## Aapko kya karna hai (sirf ye follow karo)

## 1) Repo open karo

- `https://github.com/puneet253/puneetportfolio`

## 2) Correct page par jao

- **Settings → Pages**
- **Add verified domain** wali screen se back jao.

## 3) Pages enable karo

**Build and deployment** section me ye set karo:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/ (root)**

Fir **Save** karo.

## 4) Live URL

Sahi URL hoga:

- `https://puneet253.github.io/puneetportfolio/`

> HTTP (`http://`) mat use karo, direct HTTPS use karo.

## 5) 404 aaye to ye check karo

1. Repo public hai.
2. `index.html` repo root me hai.
3. `main` branch par latest code push hai.
4. Pages settings me `main` + `/root` selected hai.
5. 2–10 min wait karke hard refresh karo.

## 6) Local se push commands

```bash
git remote -v
git branch -M main
git add .
git commit -m "portfolio update"
git push -u origin main
```

## 7) Files to edit

- `index.html` → content
- `styles.css` → design
- `script.js` → footer year

---

Agar chaho to next message me main aapko exactly bata dunga ki Pages screen par kaunsa option kis dropdown me select karna hai (line-by-line).
