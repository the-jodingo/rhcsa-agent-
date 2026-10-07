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
