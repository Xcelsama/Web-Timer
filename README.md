# Salvation Ministries — Youth Convention Timer

A simple countdown timer built for stage and session use at the Salvation Ministries youth convention. Open it, set a time, and project it. No install, no server, no build step.

## Files

This app is two files, and both need to stay together in the same folder:

- `index.html` — the app itself
- `img.jpg` — the Salvation Ministries logo shown at the top

If you host or share `index.html` on its own without `img.jpg` next to it, the logo won't load.

## Features

- **Logo up top, current time below it** — clean and uncluttered
- **Big black timer panel** — bold white monospace digits, readable from the back row
- **Presets** — one-tap 5 / 10 / 15 / 20 / 30 / 45 / 60 minute buttons
- **Custom time** — type any minutes and seconds, or tap the timer digits directly to edit them
- **Color warnings** — digits turn gold under 60 seconds, pulse red under 10
- **Chime at zero** — a short audio alert plays when time runs out (mute anytime with the Sound button)
- **Fullscreen mode** — one tap turns the screen into a clean, distraction-free stage display
- **Keyboard shortcuts** — `Space` start/pause, `R` reset, `F` fullscreen

## How to use it

1. Keep `index.html` and `img.jpg` in the same folder, then open `index.html` in any modern browser (Chrome, Safari, Edge, Firefox).
2. Pick a preset or type a custom time, then hit **Start**.
3. Tap **Fullscreen** (or press `F`) before projecting to a screen — it hides the buttons and blows the clock up to full size.

No internet connection is required to run the timer once the page has loaded — only one font family loads from the web on first open.

## Hosting it for the convention

Upload both `index.html` and `img.jpg` together to a free static host and share the link with your team:

- **Vercel** — drag the folder into a new project, or connect it to a repo
- **Netlify Drop** — drag and drop the folder at [app.netlify.com/drop](https://app.netlify.com/drop)
- **GitHub Pages** — push both files to a repo and enable Pages in settings

Or just keep both files together on the laptop/phone running the projector — it works fully offline after the first load.

## Customizing

- **Presets** — find the `presets` array in the script and change the numbers (in minutes).
- **Colors** — the `:root` block at the top of the `<style>` section holds every color as a named variable (`--navy`, `--crimson`, `--gold`, etc.).
- **Logo** — swap in your own image, keeping the filename `img.jpg` (or update the `src` in the `<img>` tag to match a new filename).

---

*Salvation Ministries — ...home of Success*
