# Six.5.One fan app (demo)

A clickable demo of the DJ 651 fan app. It's a static web app set up the same way as Bali Body Battle, so fans can add it to their home screen and it opens full screen with its own icon.

It's a demo only. There's no real audio, no payments, and no texts or emails. Everything resets when the page reloads.

## Files
- `index.html` holds the whole app, with the mix covers built in.
- `manifest.webmanifest` and `icons/` give it its name, icon and full-screen mode.
- `.nojekyll` tells GitHub Pages to serve the files exactly as they are.

## Put it online (GitHub Pages)
1. Push this folder to a new GitHub repo, for example `lee-synca/dj651-app`.
2. Go to **Settings → Pages → Deploy from branch → main / root**.
3. A minute later the app is at `https://lee-synca.github.io/dj651-app/`.

Anyone with that link can open it.

## Open it full screen on a phone
- **iPhone:** open the link in Safari, tap **Share**, then **Add to Home Screen**. Open it from the new icon.
- **Android:** open the link in Chrome, tap **⋮**, then **Add to Home screen** or **Install app**.

Opened from the icon, it runs full screen with no browser bars.

## Preview on this computer
In this folder, run `python -m http.server 8651` and open http://localhost:8651.
