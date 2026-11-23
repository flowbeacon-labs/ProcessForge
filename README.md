# ProcessForge — GitHub Pages Preview

This repository hosts a **static browser preview** of ProcessForge, a software-process management tool.

## Features in the preview
- Sample process library and new draft processes
- Activities and process overview
- RACI responsibility matrix with one-Accountable-per-activity validation
- RACI CSV export
- In-app guided help
- Browser-local persistence

## Important limitations
GitHub Pages cannot run the ProcessForge Python FastAPI / SQLite server. This preview does **not** support Jira Cloud or IBM ELM configuration scans, cross-site comparisons, account authentication, webhooks, or backend APIs. Data is stored **only in browser localStorage**, not in GitHub or a server. Do not enter credentials or confidential data.

## Enable GitHub Pages
Open **Settings → Pages** in this GitHub repository. Under **Build and deployment**, select **Deploy from a branch**, select **main** and **/(root)**, then **Save**.

Expected URL after GitHub deploys the site:
https://flowbeacon-labs.github.io/ProcessForge/

This preview is separate from the full Windows application.
