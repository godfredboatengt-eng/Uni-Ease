# uniEase — UCC Student Services

A responsive prototype for a University of Cape Coast student platform, organised around three primary services:

1. **Campus Print & Design** — file upload, print-centre selection, print/photocopy/binding and Photoshop options, collection appointments and a pre-collection payment preference.
2. **China Shopping** — assisted product requests, quotation workflow and order records.
3. **Learn Chinese** — beginner Mandarin phrases, bite-sized lessons, vocabulary practice and one-on-one lesson requests.

Supplementary areas include the student marketplace, health and pharmacy information, and other student services.

## UCC locations

The print booking interface places the named centres at **Science Market, UCC Northern Campus (New Site)**. It lists Mentor Printing / Mentor Business and Mystic Printing as supplied for this project. UCC's official campus overview describes the Northern Campus as the area commonly called "Science"; the university identifies the Sam Jonah Library as its main library on the New Site.

## Run locally

Open `index.html` in a modern browser. No build step or dependencies are required.

## Prototype features and limitations

- Demo student profile stored in browser local storage
- Print & Design appointment requests with uploaded file selection, print-centre selection, collection date/time and payment preference
- China product requests
- Mandarin lesson cards, phrase practice quiz and one-on-one lesson requests
- Supplementary marketplace, health and student service sections
- Demo cart and checkout
- Stock photography embedded from Unsplash image URLs; an internet connection is required for those photos to load

This is a front-end demonstration, not a production service. Uploaded print files are not transmitted to print shops; appointment requests and user data remain in the current browser; no live payment is processed; prices, shop opening hours, provider availability and order tracking are not connected. The language-learning video area is a placeholder until trusted video content and rights are selected. Do not enter real payment credentials or sensitive documents.

A production release needs a secure backend and database, verified student accounts, private file storage and retention controls, print-centre dashboards, confirmed price lists and availability, real payment gateway integration, China supplier/logistics integrations, licensed language-learning content, moderation and support processes.

## GitHub Pages deployment

The repository includes `.github/workflows/pages.yml`, which deploys the root folder to GitHub Pages on pushes to `main`.

One-time setup: open **Repository → Settings → Pages → Build and deployment → Source** and select **GitHub Actions**. Then open the **Actions** tab and confirm the **Deploy uniEase to GitHub Pages** run completes successfully. The expected site URL is:

https://godfredboatengt-eng.github.io/Uni-Ease/
