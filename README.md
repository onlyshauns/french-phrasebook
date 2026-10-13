# Paris Phrasebook

French phrases for a trip to Paris. Tap a phrase to hear it, show the French line to someone else, and call 112, 17, or 15. One static page. After the first visit it works offline.

## Phrases

`data/france.json` is a copy of the France file from [travel-phrasebook](https://github.com/onlyshauns/travel-phrasebook) on `cursor/phrasebook-review-fixes-f2aa`. This page uses the greetings, food, directions, shopping, numbers, and emergency sections, including the numbers 30–1000 and the shopping tip. The file also holds the other France sections so the copy stays identical. Change the file in travel-phrasebook, then copy it here.

Parentheses in forms such as `Désolé(e)` stay on screen and are left out of speech.

## Local preview

```bash
python3 -m http.server
```

Open `http://127.0.0.1:8000`. The service worker registers on `http://` or `https://`, not from a `file://` page. It stores only successful responses, and asks before reloading when a new version is waiting.

This repository does not deploy itself.
