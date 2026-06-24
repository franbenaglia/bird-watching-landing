# BirdID — Landing & legal pages

Static site for the BirdID app: landing page, privacy policy and account-deletion
page, as required by the Google Play listing. Deployed via **GitHub Pages**.

## Structure

```
index.html            Landing (English, default)
privacy.html          Privacy Policy (English)
delete-account.html   Account deletion (English)
style.css             Shared styles
es/                   Spanish versions of the three pages
.nojekyll             Serve files as-is (no Jekyll processing)
```

Each page links to its counterpart in the other language (top-right switch).

## Deploy (GitHub Pages)

1. Push this repo to `https://github.com/franbenaglia/bird-watching-landing`.
2. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
3. The site will be available at `https://franbenaglia.github.io/bird-watching-landing/`.

URLs to use in the Play Console listing:
- Privacy policy: `…/privacy.html`
- Account deletion: `…/delete-account.html`

## Contact

Support email: feedback@fab-apps.com
