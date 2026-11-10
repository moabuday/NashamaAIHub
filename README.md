# NashamaAIHub

**Jordanian Roots. Collective Intelligence. Real Impact.**

NashamaAIHub is a Jordanian-founded AI knowledge, innovation and collaboration platform. This repository holds the **design concept / interactive prototype** of the public website for **NashamaAIHub.com**, in English and Arabic (right-to-left).

> ⚠️ **Prototype notice:** Sign-in, registration, forms, submissions and support pathways are simulated in the browser and **store nothing**. Do not present this as a working membership platform. See the *Build brief* page inside the site for the services each capability needs.

## What's in this repository

| File | Purpose |
|---|---|
| `index.html` | The full website concept (single, self-contained file — styles, icons and scripts inline) |
| `favicon.svg` | Logo icon (Petra-inspired gateway with connected AI nodes) |
| `404.html` | Bilingual "page not found" page |
| `CNAME` | Custom domain for GitHub Pages: `nashamaaihub.com` |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |
| `robots.txt` | Allows search engines to index the site |

## Publish with GitHub Pages

1. Create a new repository on GitHub (for example `NashamaAIHub`) and upload **all** files from this folder to the root of the `main` branch — including the hidden `.nojekyll` file.
2. In the repository go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Source: Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/NashamaAIHub/`.

### Connect the custom domain (NashamaAIHub.com)

At your domain registrar, add these DNS records:

| Type | Host | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | `<your-username>.github.io` |

Then in **Settings → Pages → Custom domain** enter `nashamaaihub.com`, wait for the DNS check to pass, and tick **Enforce HTTPS**.

> If you are **not** ready to use the custom domain yet, delete the `CNAME` file before publishing.

## Language

The **EN | عربي** switch in the header, footer and mobile menu translates the whole site and flips the layout to right-to-left. The choice is remembered in the visitor's browser.

## Next steps toward a working platform

- Accounts & sign-in: managed identity service (e.g. Microsoft Entra External ID, Auth0, Supabase Auth)
- Submissions & member data: API + managed database + file storage
- Content publishing: headless CMS or Markdown in this repo with pull-request review
- Events & email: transactional email + webinar platform
- Newsletter: email-marketing service with double opt-in
- Payments: only after legal entity, banking and any charitable status are confirmed
- Privacy & accessibility: align with Jordan's Personal Data Protection Law and WCAG 2.2 AA

© 2026 NashamaAIHub
