# Plain Text

A tiny web app that strips formatting (bold, italic, styled lookalike letters, hidden characters) from pasted text so it works in tools like Google Translate.

## Files
- `index.html` – the whole app
- `plain-text-icon.png` – your 180x180 Home Screen icon (add this yourself; the page already links to it)

## Publish on GitHub Pages
1. Put `index.html` and `plain-text-icon.png` in the repo.
2. Commit both (editing a local copy alone does nothing).
3. Wait 1-2 minutes for Pages to update.
4. On iPhone: delete any old shortcut, quit Safari, reload the page, then Add to Home Screen.

## How it works
- Pasting into the box keeps plain text only.
- "Convert fancy styled letters" turns characters like 𝗕𝗼𝗹𝗱 and 𝘐𝘵𝘢𝘭𝘪𝘤 into normal letters.
- Other options: remove invisible characters, straighten quotes/dashes, tidy spaces, remove Markdown symbols.
- Changing an option re-cleans the text already in the box.
