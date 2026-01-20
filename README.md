# Kruze Public Website

Simple static website for public-facing pages like account deletion.

## Pages

- `delete-account.html` - Account deletion request form (required for Google Play)

## Deployment Options

### Option 1: GitHub Pages (Free)
1. Create a new repo: `kruze-website`
2. Push this folder to the repo
3. Enable GitHub Pages in repo settings
4. URL: `https://yourusername.github.io/kruze-website/delete-account.html`

### Option 2: Firebase Hosting
1. Run: `firebase init hosting` (select this folder)
2. Run: `firebase deploy --only hosting`
3. URL: `https://kruze-app.web.app/delete-account.html`

### Option 3: Vercel/Netlify (Free)
1. Connect the repo to Vercel/Netlify
2. Deploy automatically
3. Get custom domain support

## Google Play Console

Once deployed, use the URL in your Data Safety declaration:
- Account deletion URL: `https://YOUR_DOMAIN/delete-account.html`
