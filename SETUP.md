# How to publish this GitHub profile

Your profile README must live in a repo named **exactly** `ramkrushnapatra`.

## Steps

1. Go to https://github.com/new
2. Repository name: `ramkrushnapatra` (same as your username)
3. Public repo
4. Do **not** add README on GitHub (you already have one here)
5. Create repository

Then run in PowerShell from this folder:

```powershell
cd C:\Users\Admin\IdeaProjects\ramkrushnapatra
git init -b main
git add README.md
git commit -m "Add GitHub profile README"
git remote add origin https://github.com/ramkrushnapatra/ramkrushnapatra.git
git push -u origin main
```

## After push

1. Open https://github.com/ramkrushnapatra — README should show on your profile
2. Go to your profile → **Customize your pins** → pin `build-minimal-ai`
3. GitHub → **Settings** → **Profile** → add a short bio, e.g. `React · Python · FastAPI · RAG`
