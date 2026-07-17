# 📱 Put StudyFlow on your iPhone — Step-by-Step

You'll upload these files to GitHub Pages (free), then add the app to your home screen. About 5 minutes. You can do it all from your phone, but a computer makes step 3 easier.

## Step 1 — Create a free GitHub account
Go to **github.com** and sign up (free). Verify your email.

## Step 2 — Create a repository
1. Tap the **+** button (top right) → **New repository**
2. Repository name: `studyflow`
3. Make sure **Public** is selected (required for free GitHub Pages)
4. Check ✅ **Add a README file**
5. Tap **Create repository**

## Step 3 — Upload the app files
1. In your new repository, tap **Add file → Upload files**
   - *On a phone: if you don't see this button, open your browser menu and turn on "Request Desktop Site" first.*
2. Upload ALL of these files (everything in this folder except this guide):
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-180.png`
   - `icon-192.png`
   - `icon-512.png`
3. Tap **Commit changes**

## Step 4 — Turn on GitHub Pages
1. In the repository, go to **Settings** (gear icon) → **Pages** (left sidebar)
2. Under **Source**, choose **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)** → tap **Save**
4. Wait 1–2 minutes, then refresh — you'll see your link:
   **`https://YOURUSERNAME.github.io/studyflow/`**

## Step 5 — Install on your iPhone
1. Open that link in **Safari** (must be Safari, not Chrome)
2. Tap the **Share** button (square with arrow, bottom of screen)
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add**

Done! 🎉 StudyFlow now has its own icon, opens fullscreen like a real app, works offline, and **saves your data automatically on your phone** — no more export/import needed (though occasional backups are still smart, since clearing Safari website data would erase it).

## Updating the app later
If you get an updated version, just upload the new files to the same repository (they'll replace the old ones). The app on your phone updates itself the next time you open it with internet.
