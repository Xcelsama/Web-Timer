# Salvation Ministries — Youth Convention Timer

A single-file countdown timer built for stage and session use at the Salvation Ministries youth convention. Open it, set a time, and project it. No install, no server, no dependencies.

## Features

- **Salvation Ministries branding** — your logo up top, always in view
- **Live clock** — shows the current day and time above the countdown
- **Big black timer panel** — bold white digits, readable from the back row
- **Session label** — tap the small text above the timer to rename it ("Worship", "Sermon", "Games") for whoever's running the room
- **Presets** — one-tap 5 / 10 / 15 / 20 / 30 / 45 / 60 minute buttons
- **Custom time** — type any minutes and seconds, or tap the timer digits directly to edit them
- **Color warnings** — digits turn gold under 60 seconds, pulse red under 10
- **Chime at zero** — a short audio alert plays when time runs out (mute anytime with the Sound button)
- **Fullscreen mode** — one tap turns the screen into a clean, distraction-free stage display
- **Keyboard shortcuts** — `Space` start/pause, `R` reset, `F` fullscreen

## How to use it

1. Open `index.html` in any modern browser (Chrome, Safari, Edge, Firefox).
2. Pick a preset or type a custom time, then hit **Start**.
3. Tap **Fullscreen** (or press `F`) before projecting to a screen — it hides the buttons and blows the clock up to full size.
4. Tap the small label above the timer to rename the session if you want.

No internet connection is required to run the timer once the page has loaded — only the two fonts load from the web on first open.

## Hosting it for the convention

For the easiest access on any device, upload `index.html` to a free static host and share the link with your team:

- **Netlify Drop** — drag and drop the file at [app.netlify.com/drop](https://app.netlify.com/drop)
- **GitHub Pages** — push it to a repo and enable Pages in settings

Or just keep the file on the laptop/phone that's running the projector — it works fully offline after the first load.

## Customizing

Everything lives in the one `index.html` file:

- **Presets** — find the `presets` array near the top of the script and change the numbers (in minutes).
- **Colors** — the `:root` block at the top of the `<style>` section holds every color as a named variable (`--navy`, `--crimson`, `--gold`, etc.).
- **Logo** — the image is embedded directly in the file as a data URL, so it always displays even if the file is moved or shared on its own.

---

*Salvation Ministries — ...home of Success*
