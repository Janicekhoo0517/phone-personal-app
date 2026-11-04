# My Stench & Fortune

A small home-screen dental dashboard prototype for saved Waze routes and personal details.

## Publish with GitHub Pages

1. Create a **public** GitHub repository for this app. A README in the new repository is fine.
2. Upload the files in this folder to the repository's top level (so `index.html` is at the root).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/(root)`, and save.
5. When GitHub Pages finishes its first deployment, open the site URL shown on that page. It is usually `https://<your-github-name>.github.io/<repository-name>/`.
6. On iPhone, open the site in Safari, tap **Share → Add to Home Screen**, enable **Open as Web App**, and tap **Add**.

No custom domain is needed. GitHub Pages makes the site public. Personal details have no backend and stay in local storage in that browser on that device. The weather check asks for location and sends coordinates to Open-Meteo. Use fictional details while previewing; local storage is not encrypted.


The animated bear cycles through 100 bundled Shakespearean-style dental jokes; each tap picks a different joke from the one currently shown. The jokes work offline and use no API key.
