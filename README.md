# Puneet Portfolio (GitHub Pages Ready)

Ye project static portfolio website hai jo aap GitHub Pages par free me host kar sakte ho.

## 1) Repo setup (aapki new repo: `puneetportfolio`)

Agar aapne GitHub par already `puneetportfolio` repo bana li hai, to local se ye commands chalao:

```bash
git remote -v
git remote remove origin  # sirf tab jab galat origin laga ho
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/puneetportfolio.git
git branch -M main
git push -u origin main
```

## 2) GitHub Pages ON karo

1. GitHub par `puneetportfolio` repo open karo.
2. **Settings → Pages** me jao.
3. **Build and deployment** me:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
4. **Save** dabao.
5. 1-3 min rukho (kabhi kabhi 5 min).

## 3) Aapka live link kya hoga?

Agar repo ka naam `puneetportfolio` hai to link hoga:

- `https://<YOUR_GITHUB_USERNAME>.github.io/puneetportfolio/`

Example: agar username `puneetrawat` hai to link hoga:

- `https://puneetrawat.github.io/puneetportfolio/`

## 4) Apna page kaise dekho?

- Browser me upar wala live URL open karo.
- Changes ke baad dubara push karoge to site auto-update ho jayegi.

## 5) Kya edit karna hai?

- Content: `index.html`
- Design/colors/layout: `styles.css`
- Footer year: `script.js`

## 6) Quick update workflow

```bash
git add .
git commit -m "update portfolio"
git push
```

Push ke baad 1-2 min me live site update mil jayegi.
