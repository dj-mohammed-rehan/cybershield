# CyberShield

Cyber safety and digital fraud awareness, free for everyone.

CyberShield is a static website that helps people recognize and avoid online fraud. It combines an interactive scam-awareness quiz with plain-language guides on the most common types of digital fraud and how to respond to them.

**Live site:** https://dj-mohammed-rehan.github.io/cybershield/

## Features

- Interactive quiz that tests how well you spot scam messages, calls and links
- Fraud awareness guides covering common scam types and prevention tips
- Privacy policy and terms pages
- Runs entirely in the browser as a static site, no sign-up needed

## Tech stack

HTML, CSS and vanilla JavaScript. No build step. Hosted on GitHub Pages.

## Project structure

| File | Purpose |
|---|---|
| `index.html` | Homepage, quiz and fraud guides |
| `privacy.html` | Privacy policy |
| `terms.html` | Terms of use |
| `favicon.svg` | Site icon |

## Run locally

Open `index.html` in any modern browser, or serve the folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
