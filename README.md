# Vision Forge Portfolio — iPad app

A honeycomb portfolio that plays your films straight from your iPad. Nothing is uploaded: the films are saved inside the app on the iPad itself.

## Put it on GitHub (all from the iPad)

1. In Safari, sign in at github.com and create a new **public** repository, for example `portfolio`.
2. In the Files app, tap the downloaded zip to unpack it.
3. In the repository, tap **Add file → Upload files** and select every file from the unpacked folder (they all sit side by side, no subfolders). Tap **Commit changes**.
4. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
5. After a minute or two, your app is at `https://YOUR-USERNAME.github.io/portfolio/`.

## Install it on the iPad

1. Open that address in **Safari**.
2. Tap **Share → Add to Home Screen → Add**.
3. Open the app from the new icon. Always add your films from inside the installed app: it keeps its own storage, separate from Safari.

## Using it

- **Add videos** opens a menu; choose **Choose Files** to pick from the Files app. You can select several at once.
- Each film fades into the honeycomb as soon as it's ready. With 3 or more films, no two neighbouring cells show the same film.
- **Library** lets you rename films, set a category, and remove them.
- Drag to move through the honeycomb, tap a cell to play.
- After the first launch it works offline.

## Good to know

- The app stores its own copy of each film, so it uses that much space on the iPad. You can delete the original from Files afterwards if you want, but keep a backup somewhere.
- Deleting the app from the Home Screen, or clearing Safari website data in Settings, deletes its films.
- MP4 or MOV (H.264 or HEVC) play best. Very large 4K files work but take longer to add.

## Updating the design

Edit `index.html` and upload it again to the repository. The installed app picks up the new version the next time it opens with an internet connection. To change the studio name, search `index.html` for `VISION FORGE`.
