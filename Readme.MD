# RVS Technical Campus – Semester I Results Portal

A fully static, client-side result portal for **RVS Technical Campus, Coimbatore**.  
Hosted on **GitHub Pages** — no backend, no database, no server required.

🔗 **Live Site:** `https://<your-username>.github.io/<repo-name>/`

---

## 🚀 How to Host on GitHub Pages

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in.
2. Click **New repository**.
3. Name it anything, e.g. `rvs-results`.
4. Set visibility to **Public** (required for free GitHub Pages).
5. Click **Create repository**.

### Step 2 — Upload the Files
Upload these two files to the repository:
- `index.html` — the main result portal
- `logo.png` — the college logo

You can drag & drop them directly on the GitHub website, or use Git:

```bash
git init
git add .
git commit -m "Initial commit: RVS Results Portal"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repository → **Settings** → **Pages** (left sidebar).
2. Under **Source**, select **Deploy from a branch**.
3. Choose branch: **main**, folder: **/ (root)**.
4. Click **Save**.
5. Wait ~1–2 minutes, then visit:  
   `https://<your-username>.github.io/<repo-name>/`

---

## 📁 File Structure

```
/
├── index.html    # Main portal (login + results)
├── logo.png      # College logo
└── README.md     # This file
```

---

## 🔐 How Login Works

Students log in using:
- **Register Number** (e.g. `712925243061`)
- **Date of Birth** (e.g. `21/01/2008`)

All validation is done in JavaScript — no server needed.

---

## 🎓 Features

- ✅ Secure login with Reg No + DOB validation
- ✅ Subject-wise grades with Pass/Fail status
- ✅ Overall result summary (PASS / FAIL)
- ✅ 24UCS105 (Python Programming) always marked as **U / FAIL**
- ✅ Print result button
- ✅ Logout button
- ✅ Fully responsive design
- ✅ Works 100% offline after loading

---

## ⚠️ Note

This is a **static demo portal** for educational purposes.  
Grades are generated deterministically from each student's register number — they are **not real exam results**.

---

*RVS Technical Campus – Coimbatore | An Autonomous Institution | Affiliated to Anna University*