# GECHEN AI — Company Website

Static landing page for GECHEN AI, served at https://landing.gechen.org.

GECHEN AI builds agent-native products: TripPocket (travel knowledge layer for AI agents, MCP + REST),
ACP Gateway (open-source remote access to coding agents, web + iOS) and ParkNearby (iOS).

## Run locally

No build step is required.

```bash
python3 -m http.server 8080
```

## Deploy

Production runs on the Linux host from `~/services/gechen-openai-business`
(`systemctl --user` unit `gechen-openai-business`, python http.server on 127.0.0.1:4173),
behind Caddy (`landing.gechen.org` -> `127.0.0.1:4173`). Deploy with `git pull` in that directory.

Screenshots in `assets/` are cropped to avoid private paths and unrelated project names.
