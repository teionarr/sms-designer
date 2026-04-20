# iMessage Designer

Turn any dialogue into Apple-style iMessage screenshots — instantly, in the browser.

![iMessage Designer preview](https://img.shields.io/badge/built%20with-vanilla%20JS-blue?style=flat-square)

## Usage

Paste your script into the left panel using this format:

```
1 you have no savings
2 i have a digital manifestation
1 that's just a picture
2 that's just a salary
```

- `1` → received message (gray, left)
- `2` → sent message (blue, right)

The phone preview updates live on the right.

## Run locally

Just open the file — no server, no install:

```bash
open index.html
```

Or add a terminal alias for one-command launch:

```bash
echo 'alias sms="open \"$(pwd)/index.html\""' >> ~/.zshrc && source ~/.zshrc
```

Then just type `sms` anywhere.

## Features

- Live preview as you type
- Consecutive messages from the same side are grouped
- "Read" timestamp with a random evening time
- iPhone status bar with live clock
- Pure HTML/CSS/JS — zero dependencies
