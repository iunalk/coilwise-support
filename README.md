# coilwise-support

Static support, privacy and terms site for the Coilwise app (EN + TR).
Planned URL: https://iunalk.github.io/coilwise-support/ (GitHub Pages, `main` branch, root).

Hand-written HTML/CSS. No frameworks, scripts, trackers, cookies or external fonts.

```
index.html              EN home          tr/index.html
privacy/index.html      EN privacy       tr/privacy/index.html
terms/index.html        EN terms         tr/terms/index.html
support/index.html      EN support/FAQ   tr/support/index.html
assets/site.css         shared styles (Coilwise palette, light/dark, reduced motion)
assets/fonts/           IBM Plex Sans 500/600/700 (SIL OFL, see OFL.txt), self-hosted
assets/icon.png         app icon (from 11-coilwise/assets/marka/ikon_1024.png)
```

The app links to `/privacy/` and `/terms/` (`11-coilwise/lib/sabitler.dart`); keep those paths stable.

TODO before launch: real App Store / Google Play URLs (`href="#"` on both home pages).

Local preview: `python3 -m http.server 8000`, then open http://localhost:8000/.
`_onizleme/` holds local screenshots and is not committed.
