<div align="center">

# Age In Seconds

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=flat-square)](https://soumendrak.github.io/age-in-seconds/)
[![MIT License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26?style=flat-square&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-0-success?style=flat-square)](https://www.w3.org/TR/html52/)

<!-- Inline SVG logo -->
<svg width="140" height="140" viewBox="0 0 140 140" xmlns="http://www.w3.org/2000/svg">
<rect width="140" height="140" rx="24" fill="#0a0a14"/>
  <text x="70" y="55" text-anchor="middle" font-family="monospace" font-size="28" font-weight="bold" fill="#ff6b35">0</text>
  <text x="70" y="70" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#8a8a9a">seconds</text>
  <text x="70" y="100" text-anchor="middle" font-family="monospace" font-size="11" fill="#5a5a6e">❤ 0</text>
  <text x="70" y="118" text-anchor="middle" font-family="monospace" font-size="11" fill="#5a5a6e">🫁 0</text>
</svg>

**Enter your date of birth and watch your age tick up in real-time — in seconds.**

**Live:** [https://soumendrak.github.io/age-in-seconds/](https://soumendrak.github.io/age-in-seconds/)

</div>

---

## Features

- Real-time seconds counter that updates every tick
- Estimated heartbeats (~72 bpm) since birth
- Estimated breaths (~16/min) since birth
- Date of birth picker with month/day/year inputs
- Pause / Resume button to freeze the counter
- Reset button to change DOB
- Monospace digital display for precision
- Dark theme with orange accent (#ff6b35)

## How It Works

The app stores your DOB in memory, then uses performance.now() and Date arithmetic to compute elapsed time to the millisecond. Heartbeats and breaths are extrapolated using fixed rates (72 bpm, 16 breaths/min). The counter updates every 100ms using requestAnimationFrame for smooth counting.

## Usage

1. Open `https://soumendrak.github.io/age-in-seconds/` in any browser.
2. No build step, no installation, no server required.
3. Deploy anywhere — GitHub Pages, Netlify, or any static host.

```bash
git clone https://github.com/soumendrak/age-in-seconds.git
# Open index.html directly
```

## License

Licensed under the [MIT License](LICENSE).

---

<p align="center"><sub>Built with ❤️ and zero dependencies</sub></p>
