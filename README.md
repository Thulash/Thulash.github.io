# Thulashini Selvan - Cybersecurity Portfolio

A static cybersecurity portfolio website for thulashini.com, designed for GitHub Pages.

## Files
- `index.html` - website structure and content
- `styles.css` - styling and responsive layout
- `script.js` - small footer year script

## Deploy on GitHub Pages
1. Create a new public repository named `thulashini-portfolio` or `thulash297.github.io`.
2. Upload these files to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/root`, then save.
6. Your site will be available at `https://YOUR-GITHUB-USERNAME.github.io/REPO-NAME/`.

## Connect thulashini.com
1. In your repository, create or keep the `CNAME` file with:
   ```txt
   thulashini.com
   ```
2. In your domain DNS provider, add these GitHub Pages records:
   - A records for apex domain pointing to GitHub Pages IPs
   - CNAME record for `www` pointing to `YOUR-GITHUB-USERNAME.github.io`
3. In **Settings → Pages**, add `thulashini.com` under custom domain and enable HTTPS.

## Update personal links
Replace the placeholder LinkedIn and GitHub URLs in `index.html` with your real profile links.
