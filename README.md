# Puneet Portfolio (Correct GitHub Pages Setup)

## Aapka current issue kya hai?

Screenshot me aap **Account Settings → Pages (Verified domains)** me ho.
Ye personal account-level page hai, repository website publish karne ke liye nahi.

Aapko jana hai: **Repo Settings → Pages**

- ❌ Galat: `https://github.com/settings/pages`
- ✅ Sahi: `https://github.com/puneet253/puneetportfolio/settings/pages`

---

## Step-by-step (exact)

### 1) Repo Pages settings kholo

Open this exact URL in browser:

- `https://github.com/puneet253/puneetportfolio/settings/pages`

### 2) Build and deployment set karo

Waha ye options select karo:

- **Source**: `Deploy from a branch`
- **Branch**: `main`
- **Folder**: `/ (root)`
- Click **Save**

### 3) Code available hona chahiye

Repo root me ye files honi chahiye:

- `index.html`
- `styles.css`
- `script.js`

### 4) Push commands (agar code local me hai)

```bash
git remote -v
git remote add origin https://github.com/puneet253/puneetportfolio.git  # only if origin missing
git branch -M main
git add .
git commit -m "portfolio update"
git push -u origin main
```

### 5) Live link

Deploy ke baad site yaha open hogi:

- `https://puneet253.github.io/puneetportfolio/`

> First deploy ko 2–10 min lag sakte hain.

---

## Agar phir bhi 404 aaye

1. Repo public hai.
2. `main` branch me latest commit hai.
3. `index.html` repo root me hai (folder ke andar nahi).
4. Aap repo settings URL par ho, account settings par nahi.
5. Hard refresh: `Ctrl+Shift+R` (Windows/Linux) / `Cmd+Shift+R` (Mac).

---

## Files to edit

- `index.html` → text/content
- `styles.css` → colors/design
- `script.js` → year script
