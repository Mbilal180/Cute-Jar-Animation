#  Cute Jar Animation

A charming, interactive firefly-in-a-jar animation built with pure HTML, CSS, and vanilla JavaScript no dependencies, no frameworks, just vibes.

>  A tiny glass jar with a cute face holds a little world of its own,fireflies drift lazily through the air, blinking softly in the light. Click the jar and watch the sky turn to night, the fireflies lighting up like neon sparks against the dark. It's a small, peaceful thing, the kind of project you build just because it makes you smile.

---

##  Features

- **Animated fireflies** — 15–25 glowing dots float around inside the jar with randomized, looping flight paths
- **Flickering glow effect** — each firefly fades in and out independently for a realistic, organic feel
- **Cute jar face** — a smiling character with blush marks and a gently animating smile
- **Day / Night mode toggle** — click the jar to switch between a bright daytime sky and a deep blue night sky; fireflies glow neon green at night
- **Zero dependencies** — runs as a single `cute jar.html` file in any modern browser

---

##  Getting Started

No build step, no install, no config.

```bash
# Clone the repo
git clone https://github.com/your-username/cute-jar-animation.git

# Open the file
open cute jar.html
```

Or just double-click `icute jar.html`. That's it.

---

##  Usage

| Action | Effect |
|---|---|
| Click the jar | Toggle day ↔ night mode |

---

##  Project Structure

```
cute jar .html   # Everything lives here
```

---

##  How It Works

### Firefly Generation
Each firefly is a `<div>` injected into the jar via JavaScript. A randomized `@keyframes` animation is dynamically inserted into the stylesheet, giving every firefly a unique wandering path that stays within the jar boundaries and above the face.

### Night Mode
Toggling night mode adds a `.night` class to `<body>`, which cascades style changes via CSS — darker backgrounds, neon green firefly glow via `box-shadow`, and a smooth `1s` transition throughout.

### Smile Animation
The mouth uses a CSS `@keyframes` loop that gently scales the border-radius, making the character's smile feel alive without any JavaScript.

---

##  Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge). No polyfills needed.

---

##  License

MIT — free to use, remix, and share.

---

##  Contributing

Got ideas? Open an issue or a pull request. Fun improvements welcome:

- [ ] Sound effects on click
- [ ] Slider to control firefly count
- [ ] Mobile touch events
- [ ] More jar expressions (sleepy, surprised, etc.)

---

*Made with ✨ and a little bit of magic.*
