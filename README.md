# Lyno Associate Website

Ultra-simple GitHub/Vercel upload version.

## Latest fixes

- Removed all image labels/captions from photos.
- Fixed mobile light mode so the whole site becomes light.
- Keeps dark/light mode, English/Kiswahili, responsive layout, fixed header and blue Lyno styling.

## Upload to GitHub

Upload only these files:

- index.html
- package.json
- vercel.json
- .gitignore
- README.md

Do not upload `node_modules` or `dist`.

## Run locally

```bash
npm install
npm run dev
```

Open:

```bash
http://localhost:5173
```

## Deploy on Vercel

Framework Preset: Vite  
Build Command: npm run build  
Output Directory: dist  
Install Command: npm install
