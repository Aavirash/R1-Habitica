# Habitica for Rabbit R1

A [Rabbit R1 Creation](https://www.rabbit.tech/creations) that brings [Habitica](https://habitica.com) to your pocket-sized companion.

Optimized for the R1's 240×282 touchscreen — check off habits, dailies, todos, and view your stats directly from the device.

## Install

1. Scan the QR code at [install.html](https://aavirash.github.io/R1-Habitica/install.html) with your R1
2. Open the Creations card → Add via QR code
3. Get your **User ID & API Token** from [habitica.com → Settings → API](https://habitica.com/user/settings/api)
4. Enter them in the app and tap **Connect**

## Features

- Habits (tap + or − to score)
- Dailies (tap to check off)
- Todos (tap to check off)
- Rewards (tap to buy)
- HP, XP, Level, Gold, and Mana displayed at a glance

## How it works

Single HTML file. Talks directly to the [Habitica API v3](https://habitica.com/apidoc/). No backend needed. Credentials stored locally in the R1's WebView storage.

## Development

```bash
# Serve locally
python3 -m http.server 8000
# Open http://localhost:8000 in a browser
```

The R1 requires HTTPS for Creations. Deploy to GitHub Pages, Netlify, or any HTTPS host.

## License

MIT
