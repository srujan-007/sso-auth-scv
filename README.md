# Agent SSO Sign-In Journey — Beginner's Guide

Interactive training for engineers new to Service Cloud Voice (Salesforce Voice) with Amazon Connect.
Single self-contained page: `index.html` (no build step, no external requests).

## Publish with GitHub Pages
1. Create a repo (use a **private/internal** repo if this is internal material), then from this folder:
   ```
   git init -b main
   git add .
   git commit -m "Add Agent SSO beginner's guide"
   git remote add origin <your-repo-url>
   git push -u origin main
   ```
2. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.
3. After a minute the site is at `https://<owner>.github.io/<repo>/` (GitHub Enterprise: your org's Pages host).

## Notes
- `.nojekyll` makes Pages serve the file as-is.
- The page footer says internal file names should be stripped before sharing outside Salesforce.
- Presenter mode (button, top right) shows facilitator cues and the 60-minute agenda.
