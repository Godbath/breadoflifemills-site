# Bread of Life Mills landing page

This is a simple static site ready for GitHub Pages.

## Files
- `index.html` — main page
- `styles.css` — styling
- `assets/business-card-front.png` — logo image used in the hero section

## Upload to GitHub Pages
1. Create a new GitHub repository.
2. Upload all files and folders exactly as they are.
3. In GitHub, go to **Settings > Pages**.
4. Under **Build and deployment**, set:
   - **Source:** Deploy from a branch
   - **Branch:** `main` and `/ (root)`
5. Save.
6. GitHub will publish the site at your GitHub Pages URL.

## Connect your custom domain
Once the GitHub Pages site is live:
1. In the repo **Settings > Pages**, add your custom domain:
   - `breadoflifemills.com`
2. In Wix DNS, point the domain to GitHub Pages using these records:
   - `A` records for `@` to:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - `CNAME` for `www` to:
     - `<your-github-username>.github.io`
3. Wait for DNS propagation.

Replace `<your-github-username>` with your actual GitHub username.
