# Nexa Cloud public company website

This is a separate, static English marketing website for Nexa Cloud / Hawassa Business Cloud. It is not part of the live FastAPI business application and does not modify its code or database.

## Files

- `index.html` — main company website
- `styles.css` — responsive layout and styling
- `script.js` — small-screen navigation and current copyright year
- `privacy.html` — public-site privacy notice
- `404.html` — simple not-found page
- `robots.txt` — permits public search crawlers
- `assets/favicon.svg` — Nexa Cloud-style favicon

The website has no server-side code, does not include a login system, and does not save visitor submissions. Email buttons open an email draft addressed to `nexacloud.et@gmail.com`. The existing application link points to `https://hawassa-business-cloud.onrender.com`.

## Publish for free using GitHub Pages

1. Sign in to GitHub as `Hasenha`.
2. Create a **new public repository** named `nexa-cloud-website`. Do not use or overwrite the existing `hawassa-business-cloud` repository; that contains the live application.
3. On your computer, extract the supplied ZIP. Open the extracted `nexa_cloud_public_website` folder. Select and upload the *contents* of that folder into the root of the new `nexa-cloud-website` repository. Make sure `index.html` is at the repository root (not buried inside another folder).
4. Commit the uploaded website files to the new repository's `main` branch.
5. In the new repository, open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch `main`, folder `/(root)`, then click **Save**.
8. Wait for the Pages deployment to finish. GitHub Pages typically publishes to `https://hasenha.github.io/nexa-cloud-website/`. Open the repository's **Settings → Pages** area and use its displayed site link as the source of truth.
9. Check the site on both desktop and mobile. Click the app link, each navigation section, the email link, and the Privacy page.

GitHub Pages is available for public repositories on GitHub Free. Content on a published GitHub Pages site is public, so do not upload passwords, database credentials, private customer records, private application code, access tokens, or any sensitive documents into this website repository.

Official instructions: https://docs.github.com/en/pages/quickstart and https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Before wider promotion

- Confirm the company description and founder details are accurate.
- Confirm the contact email can receive messages.
- Check the currently deployed app URL before promoting it.
- Add a custom domain later if desired; the site can begin with the free GitHub Pages address.

## Contact method limitation

The contact action currently uses `mailto:`. It opens the visitor's configured email application; it does not create an on-site ticket or send email automatically. A hosted form would require a separate backend or a third-party form provider.
