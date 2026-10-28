# Neon Requiem (web test build)

A mobile action game in a single page. This folder is ready to upload to GitHub and
play through GitHub Pages on any phone, including iPhone (Safari) and Android (Chrome).

| File | What it is |
|---|---|
| `index.html` | The game. GitHub Pages opens this first. |
| `check.html` | Phone check. Confirms your phone can run the game (touch, sound, saving, screen). |
| `privacy.html` | Privacy notice. Use its address as the privacy link in an app store. |
| `apple-touch-icon.png`, `icon-192.png` | The icon shown when you add the game to your home screen. |
| `TESTING.md` | The checklist to work through on your phone. |

The game needs no internet once it has loaded, collects no data, and has no outside code.

---

## Put it online (about 10 minutes, no coding)

1. **Unzip** the download. You get a folder called `neon-requiem`.
2. Sign in at **github.com** and click **New** (or the **+** at the top right, then **New repository**).
3. Name it `neon-requiem`, choose **Public**, and click **Create repository**.
   GitHub Pages is free for public repositories. Nothing in these files is secret.
4. On the new, empty repository page, click **uploading an existing file**.
5. Open the `neon-requiem` folder on your computer, select **all the files inside it**, and drag them
   onto the GitHub page. Upload the files themselves, not the folder and not the zip.
6. Scroll down and click **Commit changes**.
7. Go to **Settings**, then **Pages** (left menu).
   Under **Build and deployment**, set **Source** to **Deploy from a branch**,
   **Branch** to **main** and the folder to **/ (root)**, then click **Save**.
8. Wait one or two minutes and refresh the Pages settings. The top will say
   **Your site is live at** `https://YOUR-USERNAME.github.io/neon-requiem/`.
9. Still on that page, tick **Enforce HTTPS** (it can take a few minutes to become available).

## Test it on your phone

1. On your phone, open `https://YOUR-USERNAME.github.io/neon-requiem/check.html`.
   Every line should say PASS (or an expected note, such as "not supported" for vibration on iPhone).
2. Tap **Start Neon Requiem**, or open `https://YOUR-USERNAME.github.io/neon-requiem/`.
3. Work through `TESTING.md`.

**iPhone:** in Safari tap **Share**, then **Add to Home Screen**. The game then opens full screen
from its own icon. Turn the silent switch off, or you will not hear the sound.

**Android:** in Chrome tap the **⋮** menu, then **Add to Home screen** (or **Install app**).

## Update the game later

1. In your repository, click **Add file**, then **Upload files**, and drop in the new `index.html`
   (same name). Click **Commit changes**.
2. Wait one or two minutes. On your phone, close the game and reopen it. If the old version still
   shows, pull down to refresh or clear the browser cache for the site.

## Before you share it widely

Open `privacy.html` in your repository, click the pencil icon, replace
`[Add your contact email]` with a personal email address, and commit the change.
