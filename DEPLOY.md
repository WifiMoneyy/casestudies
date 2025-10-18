# Deploy to Vercel - Simple Steps

**Project:** Sebastian J Case Studies Portfolio

---

## Step 1: Push to GitHub (5 minutes)

**1. Create GitHub Account (if needed)**
- Go to https://github.com/signup
- Sign up (free)

**2. Create New Repository**
- Click **+** icon (top right) → "New repository"
- Name: `case-studies`
- Set to **Public**
- **Do NOT** check any boxes
- Click "Create repository"

**3. Push Your Code**

Open terminal in your `case-studies` folder:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/case-studies.git
git push -u origin main
```

*(Replace YOUR-USERNAME with your GitHub username)*

---

## Step 2: Deploy on Vercel (2 minutes)

**1. Sign Up**
- Go to https://vercel.com
- Click "Sign Up"
- **Choose "Continue with GitHub"** (required)

**2. Import Project**
- Click "Add New..." → "Project"
- Find `case-studies` repository
- Click "Import"

**3. Deploy**
- Leave all settings default
- Click "Deploy"
- Wait 60 seconds

**4. Done!**
- Click your live URL: `https://case-studies-xxx.vercel.app`

---

## Update Your Site (Future)

Make changes, then:

```bash
git add .
git commit -m "Updated content"
git push
```

Vercel auto-deploys in 60 seconds.

---

## Troubleshooting

**"Git not found"**
- Install Git: https://git-scm.com/downloads
- Restart terminal

**"Permission denied"**
- Check GitHub username in URL is correct
- May need to setup SSH key

**Need help?**
- GitHub Docs: https://docs.github.com
- Vercel Docs: https://vercel.com/docs
