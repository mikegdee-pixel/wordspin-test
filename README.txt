WORDSPIN — playable controls prototype

Open index.html in a modern browser. Upload both index.html and dictionary.js to GitHub Pages (in the same folder). On a phone, copy the folder to a web host or serve it over your local network.

Rules
- Each round lasts 90 seconds.
- Form five-letter words across any row or down any column.
- A valid word scores once per round, including when it appears momentarily during a spin.
- Swipe slowly to drag a row/column; release quickly to spin it. Flick strength determines starting speed. Every flick travels at most one full five-position circuit, then stops; tap the moving line to stop earlier.
- Only one row/column moves at a time. Tap the spinning line to stop it.
- Switch among boards A, B, and C between rounds. A given board starts identically for every player.

Scope of this prototype
- The prototype includes the full PuzzleNook ENABLE word list filtered to 3, 4, and 5 letters (13,511 entries). The current mode scores five-letter words; shorter entries are available for future modes. A production game still needs reviewable puzzle generation.
- Results are local to the round. Social pools, accounts, server-verified scores, persistent daily boards, result sharing, and sound are future product work.
- Built in plain HTML, CSS and JavaScript without browser-only app frameworks; game rules and score functions are separate from canvas drawing and can be reused when wrapping the game for mobile apps.

Dictionary counts: 3 letters: 972; 4 letters: 3,903; 5 letters: 8,636. Other lengths are excluded.
