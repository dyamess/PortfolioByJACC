# James Adrian Celestino — Portfolio

Live: https://portfoliobyjacc.vercel.app

## Folder structure
```
index.html            the website (single file)
vercel.json           Vercel settings
assets/
  img/                profile photo
  projects/           project screenshots (16:10 or 16:9, PNG/JPG)
  docs/               CV and other PDFs
_private/             local only (ignored by git): originals, old versions
```

## Update the site
1. Edit `index.html` / add images to `assets/projects/`
2. `git add -A && git commit -m "update" && git push`
3. Vercel redeploys automatically (refresh with Ctrl+F5)
