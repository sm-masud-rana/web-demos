# Web Demos — Client Demo Websites

A single, scalable portfolio repository that holds many demo websites. One link, many sites.

**By:** Md. Masud Rana · 🌐 [mdmasudrana.xo.je](https://mdmasudrana.xo.je)

---

## 🔴 Live Demo

Once deployed (Vercel / GitHub Pages), the structure works like this:

- `/` → Main hub (all demo sites)
- `/doctor/` → Doctor Portfolio demo
- `/restaurant/` → Restaurant demo (add later)
- `/lawyer/` → Lawyer demo (add later)

---

## 🗂️ Folder Structure

```
web-demos/
├─ index.html        # Main hub — links to every demo site
├─ README.md
├─ .gitignore
└─ doctor/
    └─ index.html    # Doctor Portfolio demo site
```

---

## ➕ How to add a new site (3 steps)

1. Create a new folder with its own `index.html`, e.g. `lawyer/index.html`.
2. Add a card in the main `index.html` (copy the example card in the HTML comments).
3. Commit & push:
   ```bash
   git add .
   git commit -m "Add lawyer demo"
   git push
   ```

The new site goes live automatically at `/lawyer/`.

---

## 🛠️ Tech

- HTML, CSS, JavaScript (no build step — plain static files)
- Each site is a self-contained `index.html`

---

## ℹ️ Note

All demos are **self-directed practice projects**. They use demo/placeholder content — no real client data.
