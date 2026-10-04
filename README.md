# Lunu Jema CBO - Production Web Application

This repository contains the production-ready website for **Lunu Jema CBO** (Community Based Organization), optimized for health, empowerment, education, and resilience in Lamu Island and Mokowe, Kenya.

## Features & Improvements
- **Accessibility (WCAG 2.1 AA):** Includes dynamic skip link, explicit ARIA tags, screen reader cues, and keyboard navigation support.
- **Performance:** Clean CSS & JS with zero framework weight, responsive images, and optimized asset caching.
- **Cloudflare Pages Native:** Pre-configured with `_headers` (Security & HTTP Caching) and `_redirects`.

## Deployment to Cloudflare Pages
1. Log in to [Cloudflare Dashboard](https://dash.cloudflare.com/) and go to **Workers & Pages**.
2. Click **Create Application** -> **Pages** -> **Connect to Git** (or direct upload).
3. Set the build settings:
   - **Framework preset:** None
   - **Build command:** (Leave empty)
   - **Build output directory:** `/`
4. Deploy and bind your custom domain (`lunujema.org`).
