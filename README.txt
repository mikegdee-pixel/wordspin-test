WORDSPIN — playable controls prototype

Open index.html in a modern browser. It works directly from the local file; no server, install, account, or connection is required. On a phone, copy the folder to a web host or serve it over your local network.

Rules
- Each round lasts 90 seconds.
- Form five-letter words across any row or down any column.
- A valid word scores once per round, including when it appears momentarily during a spin.
- Swipe slowly to drag a row/column; release quickly to spin it. Flick strength determines starting speed. Every flick travels at most one full five-position circuit, then stops; tap the moving line to stop earlier.
- Only one row/column moves at a time. Tap the spinning line to stop it.
- Switch among boards A, B, and C between rounds. A given board starts identically for every player.

Scope of this prototype
- It has a deliberately limited built-in English word list for testing. A production game needs a curated dictionary and reviewable puzzle generation.
- Results are local to the round. Social pools, accounts, server-verified scores, persistent daily boards, result sharing, and sound are future product work.
- Built in plain HTML, CSS and JavaScript without browser-only app frameworks; game rules and score functions are separate from canvas drawing and can be reused when wrapping the game for mobile apps.
