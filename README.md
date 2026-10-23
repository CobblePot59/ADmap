# ADmap

Active Directory audit tracker in a single HTML file. It renders the Orange
Cyberdefense AD mindmap as an interactive checklist. No server, no build, no
network: just open `ADmap.html` in a browser.

## Usage

Double-click `ADmap.html` (or drag it into a browser).

- Click a step's chip to cycle status: `— / ✓ / ✗`. Counters show in the footer.
- Note button per step: `✎` none, `💬` exists. Click it to read/edit in a modal
  (`Ctrl/Cmd+Enter` saves, `Esc` closes).
- Commands are copyable, with `$VAR` highlighted.
- Search, zoom/pan, Expand all, Collapse all, Reset.

## Data

Progress and notes are saved in the browser's `localStorage` (key
`admap:progress`). Per browser, not synced. Reset clears everything.

## Credits

Content and layout from Orange Cyberdefense **ocd-mindmaps**:
<https://github.com/Orange-Cyberdefense/ocd-mindmaps>, by Mayfly (@M4yFly) and
contributors. ADmap only renders their work.

License: GPL-3.0, same as upstream.
