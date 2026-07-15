# 🤸 Gymnastic Club Academy — Egypt

Official website for **Gymnastic Club Academy**, a gymnastics training center in Cairo, Egypt.

Built with **plain HTML, CSS and JavaScript only** — no build step, no frameworks. Just open `index.html` or push to GitHub Pages.

---

## ✨ Features

- Fully responsive, mobile‑first design
- Egyptian localization (Cairo address, +20 phone, EGP pricing, Egyptian weekend hours, Arabic welcome line)
- Programs for ages 2 – 14
- 6 coaches (Ahmed, Mohamed, Mayar, Hassan, Reham, Khalid)
- Photo gallery, testimonials, contact form with free‑trial booking
- Scroll‑reveal animations, sticky navbar, mobile menu
- Zero dependencies — works offline

---

## 📂 Project structure

```
.
├── index.html      ← entry page (all sections)
├── styles.css      ← all styling (CSS variables, responsive layout)
├── script.js       ← mobile menu, scroll effects, form handler
├── .gitignore
└── README.md
```

---

## 🚀 Deploy to GitHub Pages (the easy way — no Actions)

Because this is a static site, GitHub Pages can serve it directly from the `main` branch — no build, no workflow.

### 1. Create a new repository on GitHub
Go to **https://github.com/new** and name it (e.g. `gymnastic-club-egypt`).
Do **not** add a README or `.gitignore` (this project already has them).

### 2. Push your files
```bash
git init
git branch -M main
git add .
git commit -m "Initial commit: Gymnastic Club Academy website"
git remote add origin https://github.com/YOUR_USERNAME/gymnastic-club-egypt.git
git push -u origin main
```

### 3. Enable GitHub Pages
On your repo on GitHub:
1. **Settings** → left sidebar **Pages**
2. Under **Source**, choose **Deploy from a branch**
3. Under **Branch**, select **`main`** and folder **`/ (root)`** → click **Save**
4. Wait ~1 minute, then open:
   ```
   https://YOUR_USERNAME.github.io/gymnastic-club-egypt/
   ```

### 4. (Optional) Custom domain like `gymnasticclub.com.eg`
- In **Settings → Pages → Custom domain**, enter your domain
- Add a `CNAME` DNS record pointing to `YOUR_USERNAME.github.io`
- Tick **Enforce HTTPS** once available

---

## 🛠️ Local preview

Just open `index.html` in any modern browser — that's it.

Or run a tiny local server so relative paths work exactly like on GitHub:
```bash
# Python 3
python -m http.server 8000
# or with Node
npx serve .
```
Then visit `http://localhost:8000`.

---

## 🎨 Customization cheat‑sheet

- **Colors:** edit the CSS variables at the top of `styles.css` (`--orange`, `--ink`, etc.)
- **Logo:** replace the `<svg>` inside `.brand` in `index.html`
- **Programs / coaches / gallery:** edit the corresponding `<section>` blocks in `index.html`
- **Contact info:** update the contact list and footer in `index.html`
- **Fonts:** change the Google Fonts `<link>` in `<head>`

---

Made with ❤️ in Cairo.
