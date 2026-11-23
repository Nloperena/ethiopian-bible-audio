# Provenance

## Voice
- Model: **Kokoro-82M v1.0** by hexgrad (https://huggingface.co/hexgrad/Kokoro-82M), **Apache License 2.0**, which allows commercial use. Its model card says it was trained only on permissive or non-copyrighted audio.
- Voice: **am_michael** (American English, male), from the same Apache 2.0 repository.
- Run locally on our own computer with kokoro-onnx (MIT) and onnxruntime. No paid or cloud speech service was used. The voice is computer generated, not a human reader.
- Settings: speed 0.9; each verse made separately and joined with 0.45 s of silence; each chapter starts with "<Book>, chapter <n>." Encoded as Opus 16 kbps mono (WebM) from a 24 kHz original.
- Text cleanup before reading: translators' square brackets and editorial marks removed; LORD and GOD read as Lord and God.

## Texts read (same as in the app)
| Books | Source | License |
|---|---|---|
| Most Old and New Testament books, and the Apocrypha | King James Version, 1769 standard text (eBible.org eng-kjv, CrossWire) | Public domain (outside the UK, where the Crown holds printing rights) |
| Psalm 151, Ezra Sutuel (4 Ezra) 7:36 to 7:105 | World English Bible (eBible.org eng-web) | Public domain dedication |
| Enoch, Jubilees | R. H. Charles, SPCK 1917 | Public domain (published 1917; Charles died 1931) |
| 1 Meqabyan chapter 1 | D. P. Curtin, 2018 (Wikisource) | Public domain release by the translator for chapter 1 |
| 1 Meqabyan chapters 2 to 4 | AI draft translated from J. Horovitz's Ge'ez excerpt (1906) | Ge'ez public domain; draft English offered freely with the app |
| 1 Meqabyan from chapter 5 on (and the end of chapter 4), all of 2 and 3 Meqabyan | Retelling in the app's own words, not scripture text | Own writing, offered freely with the app |
| 4 Baruch | AI draft translated from A. Dillmann's Ge'ez (1866) | Ge'ez public domain; draft English offered freely |
| Didascalia | J. M. Harden, SPCK 1920 | Public domain (Harden died 1938) |
| Statutes of the Apostles | G. Horner, 1904 | Public domain (Horner died 1930) |
| Apostolic Canons | G. H. Schodde, 1885 | Public domain (Schodde died 1917) |

AI drafts and retellings are labeled as such in the app and have not been reviewed by a scholar.

## License of these audio files
The underlying texts are public domain or the app's own writing. The license for the project's own material (CC BY-SA 4.0 or CC0) will be set with the app's open-source release. Until then, please credit "Ethiopian Bible app audio, voice by Kokoro-82M (Apache 2.0)".
