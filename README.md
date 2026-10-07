[![RHCSA](https://img.shields.io/badge/RHCSA-EX200-EE0000?logo=redhat&logoColor=white)](https://www.redhat.com/en/services/certification/rhcsa)
[![HTML](https://img.shields.io/badge/HTML-single%20page-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![No dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

# RHCSA Study Agent

A study companion for the **Red Hat Certified System Administrator (EX200)** exam,
delivered as a single-page web app.

## Features

- **Topic shortcuts** across the full EX200 blueprint — SELinux, LVM, Podman,
  firewalld, networking, and more
- **Quiz mode** — gives you a scenario before revealing the answer
- **Command formatting** — commands render as clean code blocks
- **Conversation memory** — multi-turn lab walkthroughs
- **Terminal aesthetic**

## Usage

Open `index.html` in a browser. No build step, no dependencies.

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## License

MIT
