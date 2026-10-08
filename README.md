# My Meal Planner — PWA

This package turns the standalone Meal Planner into an installable Progressive Web App (PWA).

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `my-meal-planner`.
2. Upload everything in this folder, keeping the `icons` folder intact.
3. In the repository, open **Settings → Pages**.
4. Choose **Deploy from a branch**, select the `main` branch and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site.
6. Open the HTTPS address on your Android phone in Chrome.
7. Use Chrome's menu and choose **Install app** (wording can vary by Chrome version).

The app is designed to work offline after its first successful load. Your meal plans and recipe edits remain stored locally on the device, so keep using the built-in backup/restore feature when moving to a new device or clearing browser data.

## Important

A PWA needs to be served from HTTPS for normal installation. Opening `index.html` directly as a local file is useful for testing but will not provide the full installable-PWA experience.
