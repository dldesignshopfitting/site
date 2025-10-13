# DL Design & Shopfitting — GitHub Pages
撒地方
### How to publish
1. Create a new GitHub repo (public): `dlshopfitting-site` (or any name).
2. Upload all files in this folder to the repo root.
3. In **Settings → Pages**, set **Source = Deploy from a branch**, **Branch = main**, **Folder = /(root)**.
4. Wait for the green Pages check, then open `https://<username>.github.io/<repo>/`.
5. (Optional) In **Pages → Custom domain**, add your domain and follow DNS instructions.

### Formsubmit redirect
- Find `<input type="hidden" name="_next" value="REPLACE_WITH_YOUR_GITHUB_PAGES_URL/thanks.html">` in `index.html` and replace with your actual Pages URL.