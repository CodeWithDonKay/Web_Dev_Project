# Barça Player Hub

FC Barcelona 2026/27 player profile, squad intelligence and fixture website.

This repository contains the packaged site in `barca-player-hub-site-v2.zip`. The deployment configuration extracts the site and starts its Node server.

## What the site includes

- Current Barça first-team player directory with player images
- Detailed player profiles, strengths, development areas and positional competition
- 2026/27 fixtures and results across all currently published competitions
- Live player-stat and fixture sync support through API-Football
- Responsive desktop/mobile UI with dark/light mode
- Server-side API key handling and caching

## Local run

Extract `barca-player-hub-site-v2.zip`, then:

```bash
cd barca-player-hub
npm start
```

Open `http://localhost:4173`.

## Live updates

Set the secret environment variable `APISPORTS_KEY` on the host. Do not commit the key to GitHub.

## Deployment

The included `render.yaml` can be used by Render. It extracts the packaged site and starts the Node server.

This is an unofficial supporter/information project and is not affiliated with FC Barcelona.
