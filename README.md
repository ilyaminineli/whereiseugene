# where is eugene?

A small, quiet page for remembering Eugene.

The live timer starts at **21 May 2026, 17:48** and displays the elapsed calendar months and days, the remaining hours/minutes/seconds, and total elapsed days.

## Run locally

Open `index.html` in a browser. No build tools, dependencies, or server are required.

## Timestamp

The timestamp is defined near the bottom of `index.html`:

```js
const absenceBegan = new Date(2026, 4, 21, 17, 48, 0);
```

JavaScript months are zero-indexed, so `4` means May. The time is interpreted in the visitor's local timezone. If 17:48 refers to a specific timezone rather than the visitor's local time, adjust the constructor to an explicit ISO timestamp with the correct UTC offset.

## GitHub Pages

In the repository settings, enable GitHub Pages and choose the `main` branch with the `/(root)` folder. The page will be served from the repository's root.
