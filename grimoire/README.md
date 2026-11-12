# Grimoire — offline music player

A Spotify-style music library that runs entirely on your device.
Add MP3s and MP4s, and Grimoire sorts them into albums and artists with their cover art.
Your music is saved inside the app on your phone or computer, so it plays with **no internet**.

## Put it on GitHub (free, about 5 minutes)

1. Sign in at **github.com** and click **+ → New repository**.
   - Name it `grimoire` (or anything you like).
   - Choose **Public** (free GitHub Pages needs a public repo; your *music* is never uploaded, only the app).
   - Click **Create repository**.
2. On the new repo page click **uploading an existing file**.
   Drag in **everything from this folder**: `index.html`, `sw.js`, `manifest.webmanifest`, `README.md` and the whole `icons` folder.
   Click **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment* pick **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. Wait a minute, refresh, and GitHub shows your link, e.g. `https://YOUR-NAME.github.io/grimoire/`.

## Install it on your phone

Open your link once while you have internet, then:

- **Android (Chrome):** tap **⋮ → Add to Home screen / Install app**.
- **iPhone (Safari):** tap **Share → Add to Home Screen**.

Open it from the home-screen icon, tap **Add**, and pick your songs. From then on it works offline.

## What's in V2

- **Design your own albums and libraries (grimoires):** name, description, theme colour and your own cover image. Albums from your files can get a colour and cover too.
- **Cinematic player with synced lyrics:** lyrics come from LRCLIB (a free database of timed lyrics). They're fetched once while you're online and kept for offline. Fine-tune the timing with **− / +**, tap **Sync** to time any song yourself, paste lyrics, or add `.lrc` files with the same name as the song.
- **Every artist listed,** featured artists included.
- **Moving covers** for music videos (MP4), made from the video itself.
- **Page-turn song changes:** swipe the cover to flick songs. Turn the Black Clover theme on/off in Settings.
- **Mini player:** the player shrinks into the mini player; on a computer you can pop it out to stay on top.
- **Share to Grimoire (Android):** share music files from other apps straight into Grimoire.

## Updates

Grimoire updates itself. New versions go to this GitHub repository; the next time you open the app with internet it loads the new version. Your music, albums and lyrics stay on your device and are not affected.

## Good to know

- Music is stored per device and per browser. Songs added on your laptop don't appear on your phone; add them on each one.
- Open **Settings → Keep my music safe** so the phone doesn't clear your library when storage runs low.
- No tags in a file? It reads the name as `Artist - Title.mp3`. Edit any song's info with the **⋯** menu.
- Use your own cover art: open an album → **⋯ → Change cover**.
- Updating the app: upload the new files to the same repo. Your library stays where it is.
