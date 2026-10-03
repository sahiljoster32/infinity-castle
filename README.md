# Infinity Castle

An open-world walk through the Infinity Castle, built with three.js. Everything runs in the browser; there is no build step.

## Put it on GitHub Pages

1. Create a new repository on GitHub.
2. Upload everything in this folder to the root of the repository: `index.html`, `manifest.webmanifest`, `README.md`, and the `audio` and `icons` folders. On github.com that is **Add file → Upload files**: drag the files and both folders in, then **Commit changes**.
3. Open **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the castle is live at `https://<your-user-name>.github.io/<repository-name>/`.

You can also double-click `index.html` to play it from your computer; the sounds still work.

## Sounds

- `audio/theme.mp3` loops as the music.
- `audio/biwa.mp3` plays whenever a biwa sounds, from the direction of the player who struck it.

To use other sounds, replace these files and keep the same names. A track you pick in the game's menu replaces the theme in that browser only.

These two clips are from the Demon Slayer soundtrack. A public repository that contains them can get a copyright takedown notice. If that worries you, use your own audio files with the same names.

## Controls

- **Computer:** W A S D to walk, Shift to sprint, Space to jump, mouse to look, E to open doors and confront a biwa player, Q for the map, F to strike the biwa, M for music.
- **Phone:** left thumb to walk, right thumb to look, and the Jump, Use, Map, Biwa and Music buttons. The game goes full screen when you enter, and the button at the top right switches it. On iPhone, Safari has no full screen for web pages: tap **Share → Add to Home Screen** and start the castle from your home screen instead.
