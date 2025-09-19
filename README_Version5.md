# Suman Muthukumaran Portfolio

This is a React + Tailwind CSS portfolio site for showcasing projects, skills, and experience.

---

## 🚀 Deployment Guide (Vercel)

### 1. Prerequisites
- Node.js and npm installed locally.
- GitHub account.
- Vercel account (free) at [https://vercel.com](https://vercel.com).

### 2. Setup Locally
```bash
# Clone the repo
git clone https://github.com/your-username/portfolio.git
cd portfolio

# Install dependencies
npm install

# Run locally
npm run dev
```
Visit `http://localhost:5173` (or the port shown in your terminal).

### 3. Prepare Assets
Place your files in the `public/assets` folder:
```
public/
  assets/
    cv/
      Suman_Muthukumaran_CV.pdf
    reports/
      Infosys_Inventory_Report.pdf
```

### 4. Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/your-username/portfolio.git
git push -u origin main
```

### 5. Deploy to Vercel
1. Go to [https://vercel.com/new](https://vercel.com/new).
2. Sign in with GitHub.
3. Import your `portfolio` repository.
4. Vercel will auto-detect React (Vite/CRA). No config needed.
5. Click **Deploy**.

Your portfolio will be live at `https://your-project-name.vercel.app`.

### 6. Test File Links
- **CV:** `https://your-project-name.vercel.app/assets/cv/Suman_Muthukumaran_CV.pdf`
- **Report:** `https://your-project-name.vercel.app/assets/reports/Infosys_Inventory_Report.pdf`

### 7. Updating
Each time you push changes to GitHub, Vercel will automatically rebuild and redeploy.

---

## 🌍 Deployment Guide (Netlify)

### 1. Prerequisites
- Node.js and npm installed locally.
- GitHub account.
- Netlify account (free) at [https://app.netlify.com](https://app.netlify.com).

### 2. Push Project to GitHub
(See steps above under **Push to GitHub**).

### 3. Deploy on Netlify
1. Go to [https://app.netlify.com/start](https://app.netlify.com/start).
2. Sign in with GitHub.
3. Click **New site from Git**.
4. Select your `portfolio` repository.
5. Set build command: `npm run build`
6. Set publish directory: `dist` (for Vite) or `build` (for CRA).
7. Click **Deploy Site**.

Your portfolio will be live at `https://your-project-name.netlify.app`.

### 4. Test File Links
- **CV:** `https://your-project-name.netlify.app/assets/cv/Suman_Muthukumaran_CV.pdf`
- **Report:** `https://your-project-name.netlify.app/assets/reports/Infosys_Inventory_Report.pdf`

### 5. Updating
Each push to GitHub will trigger an automatic rebuild and deploy on Netlify.

---

## 📦 Deployment Guide (GitHub Pages)

### 1. Prerequisites
- Node.js and npm installed locally.
- GitHub account.

### 2. Push Project to GitHub
(See steps above under **Push to GitHub**).

### 3. Install GitHub Pages Package
```bash
npm install gh-pages --save-dev
```

### 4. Update `package.json`
Add these fields:
```json
"homepage": "https://your-username.github.io/portfolio",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d dist"
}
```
For CRA replace `dist` with `build`.

### 5. Deploy
```bash
npm run deploy
```

Your portfolio will be live at `https://your-username.github.io/portfolio`.

### 6. Updating
Run `npm run deploy` after each update to publish changes.

---

## 🛠 Tech Stack
- React
- Tailwind CSS
- Vercel, Netlify, or GitHub Pages (Hosting)

---

## 📄 License
This project is free for personal and educational use.
