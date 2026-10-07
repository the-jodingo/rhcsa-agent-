[![CI](https://github.com/the-jodingo/rhcsa-agent-/actions/workflows/ci.yml/badge.svg)](https://github.com/the-jodingo/rhcsa-agent-/actions/workflows/ci.yml)
[![RHCSA](https://img.shields.io/badge/RHCSA-EX200-EE0000?logo=redhat&logoColor=white)](https://www.redhat.com/en/services/certification/rhcsa)
[![HTML5](https://img.shields.io/badge/HTML5-single%20page-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

# RHCSA Study Agent

A study companion for the **Red Hat Certified System Administrator (EX200)**
exam, delivered as a single self-contained web page.

## Table of contents

- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
- [Exam blueprint coverage](#exam-blueprint-coverage)
- [Accessibility](#accessibility)
- [License](#license)

## Features

- **Topic shortcuts** across the full EX200 blueprint
- **Quiz mode** — gives you a scenario before revealing the answer
- **Command formatting** — commands render as readable code blocks
- **Conversation memory** — keeps context across a multi-turn lab walkthrough
- **Terminal aesthetic**

## Requirements

A modern web browser. No build step, no server, no dependencies.

## Usage

```bash
git clone https://github.com/the-jodingo/rhcsa-agent-.git
cd rhcsa-agent-
python3 -m http.server 8000
```

Open <http://localhost:8000>. You can also just open `index.html` directly.

## Exam blueprint coverage

| Area | Covered |
|---|---|
| Essential tools | shell, file management, redirection, links |
| Users and groups | creation, modification, sudo policy |
| Permissions | standard, special bits, ACLs |
| SELinux | modes, contexts, booleans, troubleshooting |
| Storage | partitions, LVM, swap, filesystems |
| Services | systemd units, targets, enabling |
| Networking | static config, hostname, firewall |
| Containers | Podman, images, volumes, systemd integration |

## Accessibility

- semantic HTML with a logical heading order
- keyboard-navigable controls with visible focus states
- sufficient colour contrast on the terminal theme
- responsive down to mobile widths

## License

[MIT](LICENSE) © Joash Odingo
