# Moonside 🌙 — your personal offline music player

A liquid-glass music player that installs to your iPhone or iPad Home Screen and
works completely offline. Your music is stored inside the app itself.

## What's in this folder
- `index.html` — the whole app
- `sw.js` — offline support + smooth updates
- `manifest.json` + icons — makes it installable like a real app

## Put it online with GitHub Pages (free, ~5 minutes)

1. Go to https://github.com and log in.
2. Click **＋ → New repository**. Name it something like `moonside`.
   **Set it to Public** (GitHub Pages is free on public repos), then Create.
3. On the repo page: **Add file → Upload files** → drag all the files from this
   folder in → **Commit changes**.
4. Go to **Settings → Pages** (left sidebar).
5. Under *Build and deployment*: Source = **Deploy from a branch**,
   Branch = **main**, folder = **/ (root)** → Save.
6. Wait a minute, refresh — GitHub shows your link:
   `https://YOUR-USERNAME.github.io/moonside/`

That's your app! 🎉

### Updating the app later
Just upload the changed file(s) to the repo again (Add file → Upload files →
commit). The app refreshes itself next time you open it with internet.
**Your music, playlists, lyrics and covers are never affected by updates** —
they live in your phone's database, completely separate from the app files.

## Install on your iPhone / iPad
1. Open your GitHub Pages link in **Safari**.
2. Tap **Share** → **Add to Home Screen** → Add.
3. Open Moonside from your Home Screen — from then on it works with no internet.

## Using it
- **Import music** → Browse → pick songs from Files, iCloud, or a **plugged-in
  USB drive/SSD**. Songs are copied into the app, so they keep playing after
  you unplug the drive.
- **Sorting**: use the glass pill next to Import (or inside any playlist) —
  A–Z, Artist, Recently added, or a playlist's own "My order".
- **Artwork**: covers inside MP3/FLAC files show automatically; add your own
  photo via ⋯ on any song.
- **Lyrics**: ⋯ on a song → paste lyrics, plus an optional translation with
  matching lines. Now Playing → Lyrics shows each translated line underneath
  the original, with a show/hide toggle.
- **Sleep timer**: Now Playing → Timer ☾ — 15/30/45/60 minutes, or "End of song".
- **Playlists**: Playlists tab → New playlist, then add songs via ⋯.

## Good to know
- Deleting the app from your Home Screen (not updating it!) removes its stored
  music. Your original files elsewhere are always untouched.
- iPhones give web apps a generous but not unlimited amount of space — a few GB
  of music is usually fine.
- Supported formats on iPhone: MP3, M4A/AAC, WAV, and FLAC.
