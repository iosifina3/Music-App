# Moonside 🌙 — your personal offline music player

A liquid-glass music player that installs to your iPhone or iPad Home Screen and
works completely offline. Your music is stored inside the app itself.

## What's in this folder
- `index.html` — the whole app
- `sw.js` — offline support + smooth updates
- `manifest.json` + icons — makes it installable like a real app

## Updating your existing app
Just upload these same files to your GitHub repo again (Add file → Upload
files → commit) — they'll overwrite the old ones. Next time you open
Moonside with internet on, it quietly picks up the new version.
**Your music, playlists, lyrics and artwork are never affected by updates —**
they live in your phone's own database, completely separate from these files.

## First-time setup (GitHub Pages, free)
1. Go to github.com, sign up/log in.
2. **＋ → New repository**, name it `moonside`, keep it **Public**, Create.
3. **Add file → Upload files** → drag in everything from this folder → Commit.
4. **Settings → Pages** → Source: Deploy from a branch → Branch: **main**,
   folder **/ (root)** → Save. Wait a minute, refresh for your link.
5. Open that link in **Safari** on your iPhone → Share → **Add to Home Screen**.

## What's new in this version
- **Lyrics now live inline, Spotify-style** — no more separate pop-up. Open
  Now Playing and scroll down past the controls to reveal the lyrics right
  there on the same screen (or tap the **Lyrics** button to jump straight
  down to them).
- **Fixed a couple of lyrics glitches**: synced lyrics were re-triggering
  their auto-scroll several times a second (which felt jittery/fighting your
  own scrolling), and the whole lyrics list was rebuilding — resetting your
  scroll position — every time you tapped something unrelated like shuffle
  or repeat. Both are fixed: the highlighted line only moves when it
  actually changes, auto-scroll only happens once you've scrolled down to
  lyrics yourself, and the list only rebuilds when the song changes.
- **.lrc file support** — if your songs came with a matching `.lrc` file
  (same filename, different ending), select it alongside the song when you
  Import, and its synced lyrics attach automatically — no manual tapping
  needed. You can also add one later via a song's ⋯ → **Import .lrc**.
- **Sleek custom icons** for play/pause, next, previous, shuffle and repeat.
- **Synced lyrics** — tap along with a song once to time each line yourself
  (or import a .lrc, above), then watch the words highlight in time,
  Apple-Music style. Tap any line to jump there.
- **Loop a section** — in Now Playing, tap **Loop** once to mark the start,
  again to mark the end, and it'll repeat that section until you turn it off.
- **Multi-select** — tap **Select** in your Library (or inside a playlist) to
  tick several songs at once, then add them all to a playlist, queue them,
  play them next, or delete/remove them in one go.
- **Playlists: pin, reorder, and folders** — pin favourites to the top, use
  **Reorder** to nudge playlists up/down, and optionally group playlists into
  folders (totally optional — ungrouped playlists work exactly as before).
- **Shuffle play** — a dedicated button on any playlist to shuffle straight
  through it (properly cycles every song once before repeating, like Spotify).
- **Release year** — shown in Now Playing next to the artist/album, and
  editable in a song's details if it's missing.
- **Play Next / Add to Queue** — from a song's ⋯ menu (or a multi-selection),
  plus a **Queue** button in Now Playing to see and manage what's coming up.
- **The Guide tab is gone** — replaced with a lean **Settings** tab holding
  just Backup & restore.

## Using it
- **Import music** → Browse → pick songs from Files, iCloud, or a **plugged-in
  USB drive/SSD**. They're copied into the app, so they keep playing after
  you unplug the drive. If a song has a matching `.lrc` file, select it in
  the same picker and its synced lyrics come in automatically.
- **Artwork**: covers inside MP3/FLAC files show automatically; add your own
  photo via ⋯ on any song.
- **Lyrics & translation**: ⋯ on a song → paste lyrics, plus an optional
  translation with matching lines. In Now Playing, scroll down past the
  controls to see them, with translated lines sitting under the originals
  and a show/hide toggle.
- **Sleep timer**: Now Playing → Timer ☾ — 15/30/45/60 minutes, or "End of song".
- **Backup & restore**: Settings tab → Create backup saves a small file (to
  Files/iCloud) with your lyrics, translations, synced timing, artwork,
  playlists and folders — not the audio, which you re-import from your drive.
  Restore matches everything back up automatically by title and artist.

## Good to know
- Deleting the app from your Home Screen (not updating it!) removes its
  stored music. Your original files elsewhere are always untouched.
- iPhones give web apps a generous but not unlimited amount of space — a few
  GB of music is usually fine.
- Supported formats on iPhone: MP3, M4A/AAC, WAV, and FLAC.
