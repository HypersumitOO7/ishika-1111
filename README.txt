# Ishika — 11:11 surprise website

## Publish free with GitHub Pages
1. Sign in or create a free account at https://github.com/
2. Create a new **public** repository, for example `ishika-1111`.
3. Upload `index.html` to the repository root.
4. (Optional) Upload `music.mp3` beside `index.html` and a `photos` folder for your images.
5. In the repository, open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
7. Wait for GitHub Pages to publish. Your site will be at `https://YOUR-USERNAME.github.io/ishika-1111/`.

## Personalize the website
Open `index.html` in a text editor and find `const CONFIG = {` near the bottom.
Edit her name, nickname, apology, love message, compliment cards, wishes and final message there.

## Add music
Upload a royalty-free or personally licensed MP3 named `music.mp3` to the repository root.
The music button will play it after the visitor taps Play.

## Add photos
The current build uses no personal photos, so there are no invented memories. You can add your own gallery later by editing the HTML.

## Test before publishing
In `CONFIG`, temporarily set `previewMode: true` to preview the chapters immediately.
**Set it back to `false` before publishing.**

## Important timing note
The countdown uses the visitor's device clock and the target time `2026-11-11T23:11:00+05:30`.
This is suitable for a fun surprise, but it is not secure access control: a visitor can alter their device clock or inspect the public website source. GitHub Pages is static hosting and does not provide a secret server-side lock.
