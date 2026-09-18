# Andrew & Sarah

The engagement invitation — Saturday 26 September 2026, 8pm,
Maryland Wedding Hall, Assiut.

Live at **https://andrewemad98.github.io/andrew-sarah/**

## Editing it

Everything you'd change lives in one block near the top of the script in
`index.html`, marked `EDIT EVERYTHING HERE`: names, date, venue, dress
code, phone, and the photo list. Fields written as `{ en: "…", ar: "…" }`
appear in both languages; a floating button switches between them.

The event date carries Cairo's UTC offset (`+03:00`) so the countdown
reads the same for guests abroad. Egypt moves to `+02:00` in late October.

## Photos

In `photos/`, numbered in the order they appear. A landscape shot needs
`wide: true` in the config so the drifting ribbon frames it correctly.
The gallery tiles without gaps at 4, 5, 6, 8, 9 or 12 photos.

## Note on the Claude artifact copy

The same page is also published as a Claude artifact, where the host adds
the `<!DOCTYPE>`/`<head>` wrapper itself. That copy is this file with
everything above `</head>` and the closing `</body></html>` stripped off.
