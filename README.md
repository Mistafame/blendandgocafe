# Blend & Go Café — GitHub Pages Website (Opening Soon)

## Add your logo
Upload your logo image into this folder and name it **logo.png**.

## Publish on GitHub Pages
1) Create a GitHub account.
2) Create a new repository (any name).
3) Upload these files to the repo:
   - index.html
   - styles.css
   - script.js
   - logo.png

4) Repo → **Settings → Pages**
   - Source: Deploy from a branch
   - Branch: main / (root)
   - Save

GitHub will give you a URL like:
https://YOURUSERNAME.github.io/REPO/

## Connect your custom domain (blendandgocafe.com)
### In GitHub:
Repo → Settings → Pages → Custom domain:
- Enter: **blendandgocafe.com**
- Save
- Enable **Enforce HTTPS** (after it appears)

### In GoDaddy DNS:
A records (root / @):
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

CNAME (www):
- www → YOURUSERNAME.github.io

Note: DNS can take from a few minutes up to 24 hours.
