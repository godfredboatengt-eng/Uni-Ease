# uniEase — UCC Student Services

A responsive, mobile-friendly prototype for a University of Cape Coast student services platform.

## Run locally
Open `index.html` in a modern browser. No build step or dependencies are required.

## Prototype features
- Student profile sign-up (demo details stored in browser local storage)
- China product discovery and assisted-order requests
- Student marketplace for books, stationery, furniture, electronics and appliances
- Student service listings and peer tutoring, including optional photo uploads
- Smart printing requests with document selection and collection preferences
- Health and everyday essentials catalogue plus an illustrative consultation request
- Cart and demo checkout with MTN Mobile Money, Telecel Cash and payment-on-delivery options
- Orders and booking history

## Publish with GitHub Pages
The repository includes a GitHub Actions workflow at `.github/workflows/pages.yml`.
1. In the repository, open **Settings → Pages**.
2. Under **Build and deployment**, select **GitHub Actions** as the source if it is not already selected.
3. Open the **Actions** tab and check the **Deploy uniEase to GitHub Pages** workflow.
4. After a successful deployment, the site will be available at:
   https://godfredboatengt-eng.github.io/Uni-Ease/

## Important prototype limitations
This is a front-end demonstration, not a production service. Authentication and student verification, cloud file storage, real-time messaging, delivery tracking, live mobile-money payments, pharmacy fulfilment and hospital consultations are not connected. Demo data is stored in the current browser and is not shared between users or devices. Do not enter real passwords, payment credentials or sensitive medical information.

A production release should add a secure backend and database, verified student accounts, private file storage, role-based administration, moderation and reporting, privacy controls, and approved payment, pharmacy and healthcare integrations.
