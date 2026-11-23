# Ethiopian Bible audio

Recorded audio for the free, ad-free Ethiopian Bible app (https://ethiopian-bible-lyart.vercel.app).
One computer-generated voice reads each chapter. No ads, no tracking, and no account is needed.

Files are served with GitHub Pages at https://nloperena.github.io/ethiopian-bible-audio/

## Layout
- `index.json`: list of every chapter that is ready: `{voice, base, ext, type, ch:{book:[chapters]}, kb:{"book/n":KB}}`
- `<book>/<n>.webm`: the chapter audio. Opus, 16 kbps, mono, in WebM (plays in Chrome, Android, Firefox, and Safari on iOS 17.4 or newer).
- `<book>/<n>.json`: timings `{"v":voice,"s":speed,"d":seconds,"t":[[verse or null, start, end], ...]}`, one row per verse or paragraph in reading order, so an app can highlight the verse being read.

Book ids match the app (gen, exo, ..., eno, jub, 1mq, 2mq, 3mq, 4ba, ..., rev, did, sta, apc).

Chapters are added in batches while the rest are still being made. See PROVENANCE.md for how the audio was made and where the texts come from.
