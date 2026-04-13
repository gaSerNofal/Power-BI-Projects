# 🚀 How to Push Your Power BI Projects to GitHub

Follow these steps to create your GitHub repo and push all your projects.

---

## Step 1 — Create the Repo on GitHub

1. Go to [github.com](https://github.com) and log in
2. Click the **+** button (top right) → **New repository**
3. Fill in:
   - **Repository name**: `Power-BI-Projects`
   - **Description**: `Power BI dashboards — Sales, Operations, Finance & more`
   - **Visibility**: Public ✅ (so it shows on your profile)
   - ❌ Do NOT check "Add a README file" (you already have one)
4. Click **Create repository**
5. Copy the repo URL — it will look like:
   `https://github.com/YOUR_USERNAME/Power-BI-Projects.git`

---

## Step 2 — Set Up Your Folder Structure Locally

On your computer, create this folder structure:

```
Power-BI-Projects/
│
├── README.md                        ← Main portfolio README
│
├── AdventureWorks-v1/
│   ├── README.md
│   ├── AdventureWorks_v1.pbix
│   └── screenshots/
│       ├── overview.png
│       └── ...
│
├── AdventureWorks-v2/
│   ├── README.md
│   ├── AdventureWorks_v2.pbix
│   └── screenshots/
│
├── Airline-Delays/
│   ├── README.md
│   ├── Airline_Delays.pbix
│   ├── Data_Cleaning.ipynb
│   └── screenshots/
│
├── Kickstarter-Projects/
│   ├── README.md
│   ├── Kickstarter.pbix
│   └── screenshots/
│
└── Top250-Movies-IMDb/
    ├── README.md
    ├── Top250_Movies.pbix
    └── screenshots/
```

---

## Step 3 — Open Git Bash / Terminal

Navigate into your project folder:

```bash
cd path/to/Power-BI-Projects
```

Example on Windows:
```bash
cd C:/Users/Gaser/Desktop/Power-BI-Projects
```

---

## Step 4 — Initialize Git & Push

Run these commands **one by one**:

```bash
# 1. Initialize Git in the folder
git init

# 2. Add all files to staging
git add .

# 3. Create your first commit
git commit -m "Initial commit: Add all Power BI projects and READMEs"

# 4. Rename branch to main (GitHub default)
git branch -M main

# 5. Connect to your GitHub repo (replace YOUR_USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/Power-BI-Projects.git

# 6. Push everything to GitHub
git push -u origin main
```

✅ Done! Your projects are now live on GitHub.

---

## Step 5 — Adding Screenshots Later

After you take screenshots of your dashboards:

```bash
# Add the new screenshot files
git add .

# Commit with a clear message
git commit -m "Add dashboard screenshots for [Project Name]"

# Push to GitHub
git push
```

---

## Step 6 — Updating a Project Later

Whenever you update a `.pbix` file or README:

```bash
git add .
git commit -m "Update [Project Name] dashboard"
git push
```

---

## ⚠️ Notes on .pbix Files

- `.pbix` files can be **large** (sometimes 50MB+)
- GitHub has a **100MB file size limit**
- If a file is too large, you can use [Git LFS](https://git-lfs.github.com/) (Large File Storage)

To set up Git LFS for `.pbix` files:
```bash
git lfs install
git lfs track "*.pbix"
git add .gitattributes
git add .
git commit -m "Track .pbix files with Git LFS"
git push
```

---

## 💡 Tips

- Always write clear commit messages so you know what changed
- Add screenshots BEFORE pushing — it makes your profile much more impressive
- You can pin this repo on your GitHub profile from your profile page
